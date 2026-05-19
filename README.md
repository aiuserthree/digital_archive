# digital_archive

## Vercel

모든 프로젝트의 **Root Directory**는 **`UI 시안`** 이다.

| 프로젝트 | URL | 설정 |
|----------|-----|------|
| `digital-archive-phi` | https://digital-archive-phi.vercel.app/ | `vercel.json` → 연구자용 챗봇(젠스파크).html |
| `digital-archive-chat-standalone` | https://digital-archive-chat-standalone.vercel.app/ | `vercel.standalone.json` → chat for theologian.html |
| `digital-archive-member-genspark` | 배포 후 확인 | `vercel.member-genspark.json` → 성도용 챗봇(젠스파크).html |
| `digital-archive-member-chat` | 배포 후 확인 | `vercel.member-chat.json` → chat for member.html |

`digital-archive-phi` 외 프로젝트는 Git 푸시만으로는 갱신되지 않을 수 있다. `UI 시안`에서 `npx vercel deploy --prod -A <설정파일>` 로 배포한다. 자세한 절차는 `.cursor/rules/vercel-deploy.mdc` 참고.

### `index.html` (저장소 루트)

로컬·루트 디렉터리 미리보기용으로 **`연구자용 챗봇(젠스파크).html`** 과 동기화한다.
