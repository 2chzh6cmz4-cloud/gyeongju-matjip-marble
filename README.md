# 경주 맛집마블 V2

아이폰/안드로이드에서 바로 쓸 수 있도록 GitHub Pages용으로 만든 정적 PWA입니다.

업로드할 파일은 루트에 아래 4개만 있으면 됩니다.

- index.html
- manifest.json
- sw.js
- icon.svg

GitHub Pages는 Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save 로 설정하세요.

iPhone: Safari → 공유 → 홈 화면에 추가
Android: Chrome → 메뉴 → 앱 설치 또는 홈 화면에 추가

데이터는 서버가 아니라 브라우저 localStorage에 저장됩니다.
