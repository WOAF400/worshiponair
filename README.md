# Worship On Air 사이트

GitHub Pages로 배포하는 정적 사이트입니다. 빌드 과정이 없습니다.

## 파일
- `index.html` — 사이트 본체 (메뉴·페이지·글 내용이 모두 들어 있음)
- `network-map.html` — 네트워크 지도
- `support.js` — 사이트 실행 파일 (수정하지 마세요)
- `images/` — 로고와 교회 사진
- `.nojekyll` — GitHub Pages가 파일을 그대로 서비스하도록 하는 표시

## 배포 방법
1. GitHub에서 새 저장소(Repository)를 만듭니다. 예: `worshiponair-site`
2. 이 폴더의 파일 전체를 저장소 맨 위(루트)에 업로드합니다.
3. 저장소 **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)** → Save
4. 1~2분 뒤 `https://계정이름.github.io/저장소이름/` 에서 열립니다.

## 도메인(worshiponair.org) 연결
- Settings → Pages → Custom domain에 `worshiponair.org` 입력
- 도메인 업체 DNS에 GitHub 안내대로 A 레코드(185.199.108.153 등 4개) 또는 CNAME을 추가
- Enforce HTTPS 체크

## 글 올리는 방법
Claude에게 글 작성을 요청해 `index.html`을 새로 받아서, 저장소의 `index.html`을 교체(업로드)하면 반영됩니다.

## 알아둘 점
- 모든 사진이 `images/` 폴더에 들어 있어서 Wix를 해지해도 사진이 유지됩니다.
- 신청·문의·구독 입력란은 화면만 있고 실제로 전송되지 않습니다. 배포 전에 Formspree 등을 연결해야 합니다.
