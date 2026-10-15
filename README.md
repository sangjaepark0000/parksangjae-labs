# parksangjae labs

`labs.parksangjae.com`에서 공개할 개인 프로젝트 소개 허브입니다.

## 구조

- `/` — 프로젝트 목록
- `/pknu-lms-sync/` — PKNU LMS Sync 소개와 설치 안내
- `dist/` — Cloudflare Pages 배포 디렉터리

## 로컬 확인

```bash
python -m http.server 4173 --directory dist
```

브라우저에서 `http://localhost:4173`을 엽니다.

## Cloudflare Pages

- Framework preset: `None`
- Build command: 비워 둠
- Build output directory: `dist`
- Production branch: `main`
- Custom domain: `labs.parksangjae.com`

Cloudflare Pages 프로젝트 `parksangjae-labs`가 이 GitHub 레포와 연결되어 있어
`main` 브랜치에 푸시할 때마다 자동 배포됩니다.
