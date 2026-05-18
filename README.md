# digital_archive

## Vercel

1. Vercel 대시보드 → 해당 프로젝트 → **Settings → General → Root Directory** 를 반드시 **`UI 시안`** 으로 둔다. (저장소 루트로 두면 `/` 가 404가 된다.)
2. **`UI 시안/vercel.json`**: `/` 를 **`챗봇(연구자).html`** 로 rewrite 한다. 파일명에 괄호 `()` 가 있어 `destination` 은 URL 인코딩 경로를 사용한다.
3. 설정 변경 후 **Redeploy** 한다.
