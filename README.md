# lms-site

LMS 소개 페이지 — https://lms.mint-soft.com

정적 HTML 한 벌이다. `main` 에 올리면 GitHub Pages 가 그대로 내보낸다(빌드 없음). 도메인은 `CNAME` 파일이 정한다.

- `index.html` 본문과 스타일
- `assets/` 제품 화면(시연용 데이터로 찍은 것)
- `robots.txt` · `sitemap.xml` · `llms.txt` 검색 엔진과 AI 답변 엔진용. 본문의 기능·사양·FAQ 를 고치면 `llms.txt` 와 `index.html` 의 JSON-LD 도 같이 고친다
- `assets/og.png` 공유 미리보기 이미지(1200×630)

미리 보기: `python3 -m http.server 4000` 후 http://localhost:4000
