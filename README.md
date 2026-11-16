# 무가입 무료 PDF

가입 없이 브라우저에서 PDF를 편집하는 웹 프로그램입니다. 파일은 서버로 전송되지 않고 내 기기 안에서만 처리됩니다.

## 기능
- PDF 열기, 여러 PDF 합치기, 빈 쪽 추가(기존 쪽과 같은 크기)
- 펜, 형광펜(6색), 글자(글꼴 선택), 이미지 넣기
- 넣은 항목 클릭 선택 → 이동 / 크기 조절 / 삭제, 글자 내용 편집
- 쪽 회전, 순서 변경(축소판 드래그), 쪽 삭제, 선택한 쪽만 추출
- 저장 시 파일 이름 지정, 형식 선택(PDF / JPG / PNG)

## GitHub Pages로 올리는 방법
1. GitHub(https://github.com)에 로그인합니다.
2. 오른쪽 위 **+ → New repository**를 누릅니다.
3. Repository name에 영문 소문자 이름(예: `free-pdf`)을 쓰고, **Public**을 선택한 뒤 **Create repository**를 누릅니다.
4. 새 저장소 화면에서 **uploading an existing file**을 누르고, 이 폴더의 `index.html`과 `README.md`를 끌어다 놓습니다.
5. 아래쪽 **Commit changes**를 누릅니다.
6. 저장소의 **Settings → Pages**로 갑니다.
7. Build and deployment의 Source를 **Deploy from a branch**로, Branch를 **main**, 폴더를 **/(root)**로 고르고 **Save**를 누릅니다.
8. 1~2분 뒤 Pages 화면 위쪽에 `https://내아이디.github.io/free-pdf/` 주소가 나타납니다.

## 수정해서 다시 올리기
저장소 첫 화면 → **Add file → Upload files**에서 같은 이름(`index.html`)의 파일을 올리고 Commit하면 덮어써집니다. 반영까지 1~2분 걸립니다.

## 알아둘 점
- 인터넷 연결이 필요합니다. 라이브러리(PDF.js, pdf-lib)는 cdnjs에서, 이미지 저장용 JSZip은 jsDelivr에서, 글꼴은 Google Fonts에서 불러옵니다. PDF 내용은 이 서버들로 전송되지 않습니다.
- 사용한 라이브러리: PDF.js(Apache-2.0), pdf-lib(MIT), JSZip(MIT 또는 GPL-3.0 중 선택), 글꼴은 Google Fonts의 오픈 폰트 라이선스(OFL) 글꼴입니다.
- GitHub Pages는 온라인 사업, 전자상거래, 상업적 SaaS를 무료로 운영하는 용도로는 허용되지 않습니다. 유료화나 광고를 붙일 계획이면 다른 호스팅(Cloudflare Pages 등)으로 옮기세요.
- 광고나 접속 통계 도구를 넣으면 화면의 “서버 저장 없음” 문구와 맞는지 다시 확인하세요.
