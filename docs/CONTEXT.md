# Parksangjae Labs context

## Identity

Parksangjae Labs is a public workbench for things Park Sangjae wants to make,
quickly assembled prototypes, and small tools that grow into something usable.
It records the movement from a question to an experiment, not only polished
outcomes.

The guiding sentence is:

> 만들고 싶은 것부터 빠르게 만든 프로토타입까지 공개적으로 쌓아가는 작업대.

## Relationship to other places

- `parksangjae.com` holds writing, thoughts, and learning notes.
- `labs.parksangjae.com` introduces ideas, experiments, prototypes, and tools.
- Each project repository holds source code and detailed technical documents.

Labs should link to those sources rather than duplicate long-form writing or
maintenance documentation.

## Public stages

### Idea

A problem, curiosity, or intended experience worth making visible before code
exists. Describe the motivation, intended shape, central hypothesis, and next
experiment. Be explicit that it is not implemented yet when relevant.

### Prototype

The central interaction or technical path has been tried. Describe what works,
what was deliberately omitted, the known limitations, and what should be tested
next.

### Usable

Someone other than the author can reasonably use it within a stated scope.
Provide a clear entry point, quick start, boundaries, and links to the public
source or documentation.

### Paused

The work is on hold but its question, approach, or result remains useful to
share.

### Archived

The experiment is concluded or no longer maintained. Preserve the context and
make that status unambiguous.

## Default project-page content

Every entry should answer, in language appropriate to its stage:

1. What prompted this?
2. What is being proposed or tested?
3. What exists today?
4. What are the important limits?
5. What happens next, or where can someone try it?

An entry does not need a source repository or runnable demo when the honest
stage is `idea`. Avoid invented certainty, inflated claims, and artificial
completeness.

## Publishing boundary

Publishing to Labs normally means publishing an introduction page and project
card. It does not automatically make another repository public or deploy a new
backend, database, paid service, or secret-bearing environment. Those are
separate decisions.

The production site is deployed from the `main` branch of
`sangjaepark0000/parksangjae-labs` through Cloudflare Pages at
`https://labs.parksangjae.com`.
