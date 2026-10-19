# 매쓰로그 과일 모찌 예약

성신여고 수학 동아리 매쓰로그의 축제 부스 예약 앱이에요.

- 사이트: https://mathlog-mochi.netlify.app (Netlify가 `main` 브랜치를 자동 배포)
- 화면: `public/index.html`
- 데이터: Firebase 프로젝트 `mathlog-mochi`의 Firestore
- 보안 규칙: `firestore.rules` — 바꾸면 Firebase 콘솔 **Firestore → 규칙**에 붙여넣고 게시해야 반영돼요 (Netlify로는 반영되지 않아요).
- 관리자 추가: `firestore.rules`의 `isAdmin` 목록에 이메일을 넣고, Firebase **Authentication → 사용자 추가**로 계정을 만들어요.
