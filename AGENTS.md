# Parksangjae Labs working agreement

## Purpose

This repository powers `labs.parksangjae.com`, a public workbench for things
Park Sangjae wants to make, quick prototypes, and tools released for others.
It is not restricted to finished products or portfolio pieces.

Read `docs/CONTEXT.md` before adding or substantially changing a project page.

## Content rules

- Use one delivery stage: `idea`, `prototype`, or `released`.
- Track activity separately as `active`, `paused`, or `archived`.
- An idea may be published without code or a repository. Do not present an
  intended feature as implemented.
- Keep detailed technical and installation documentation in the project's own
  repository. Labs should explain the project and link to the source of truth.
- Link only to resources that are public and verified.
- Never publish secrets, private URLs, personal data, or private repository
  details.
- State unofficial affiliation and important usage boundaries where relevant.

## Site conventions

- Static output lives in `dist/`.
- Project pages use stable lowercase hyphenated paths such as `/project-name/`.
- Preserve the existing editorial visual language and semantic HTML.
- Keep canonical URLs, project counts, navigation, and metadata in sync.
- Check both mobile and desktop layouts for visual changes.
- Do not modify the existing `parksangjae.com` blog or unrelated DNS records.

## Verification and deployment

Serve locally with:

```bash
python -m http.server 4173 --directory dist
```

Check affected routes and links before committing. The `main` branch is linked
to the Cloudflare Pages project `parksangjae-labs`; a push triggers production
deployment. Use the installed `cf` CLI to verify the deployment and the
`labs.parksangjae.com` custom domain after publishing.
