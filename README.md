# Do Geonwoo Portfolio

정적 HTML, CSS, JavaScript로 만든 도건우 포트폴리오 사이트입니다.

## 구조

- `index.html`: 페이지 마크업
- `style.css`: 반응형 스타일과 현대백화점 로고 톤 기반 컬러 시스템
- `script.js`: 스크롤 인터랙션, 메뉴, 프로젝트 필터
- `assets/`: 포트폴리오 PDF와 미리보기 이미지

## 로컬 실행

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 열면 됩니다.

## GitHub Pages 배포

GitHub에서 `woodgeon.github.io` 저장소를 만든 뒤 아래 명령으로 배포할 수 있습니다.

```bash
git init
git add .
git commit -m "Create portfolio website"
git branch -M main
git remote add origin https://github.com/woodgeon/woodgeon.github.io.git
git push -u origin main
```

배포 후 `https://woodgeon.github.io`로 접근할 수 있습니다.
