# 공개 페이지 모음 사이트

GitHub Pages로 배포되는 정적 사이트다. 주소: https://eetlkeu-pixel.github.io/io/

## 새 페이지 추가 규칙
1. 페이지마다 폴더 하나: `<영문-소문자-하이픈>/index.html` (예: `f1-movie/index.html`)
2. `pages.json` 배열에 항목 추가: `path`(끝에 `/`), `title`, `description`, `date`(YYYY-MM-DD)
3. 루트 `index.html`은 `pages.json`을 읽어 목록을 자동으로 그린다. 직접 수정할 필요 없다.
4. `main` 브랜치에 커밋·푸시하면 1~2분 뒤 반영된다.

claude.ai 아티팩트 링크를 받으면 Artifact 도구의 `read`로 HTML을 받아 위 규칙대로 넣는다.
