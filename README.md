# blossominkyung.github.io

Mindy의 개인 포트폴리오 사이트. 빌드 과정 없는 순수 HTML/CSS이며 GitHub Pages로 서빙됩니다.

## 구조

```
.
├── index.html      # 페이지 내용 (Bio / News / Projects / Writing)
├── style.css       # 스타일 (라이트·다크 모드, 반응형)
├── images/         # 프로필 사진, 프로젝트 썸네일
│   ├── profile.jpg     # 프로필 사진 (넣으면 자동 표시)
│   ├── project1.png
│   └── favicon.ico
├── .nojekyll       # GitHub Pages가 Jekyll 처리 없이 원본 HTML을 서빙
└── README.md
```

## 편집 방법

- **소개 글**: `index.html`의 `<header class="bio">` 안 문단을 수정.
- **프로필 사진**: `images/profile.jpg` 파일 추가.
- **프로젝트 추가**: `index.html`의 `<article class="item">` 블록을 복사해 붙여넣기.
- **색상/폰트**: `style.css` 상단 `:root` 변수 수정.

## 로컬 미리보기

빌드가 필요 없습니다. 브라우저로 `index.html`을 바로 열거나:

```bash
python3 -m http.server 8000
# http://localhost:8000 접속
```

## 배포

`main` 브랜치에 push하면 GitHub Pages가 자동으로 배포합니다.
저장소 Settings → Pages → Source: `main` / `/ (root)` 로 설정.

공개 주소: https://blossominkyung.github.io
