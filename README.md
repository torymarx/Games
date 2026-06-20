# Games Dashboard

이 폴더는 GitHub Pages용 게임 허브입니다. 현재 Orbit Dodge, Blink Catch, Color Tap을 모아뒀습니다.

## 구조
- `index.html` — 메인 대시보드
- `orbit-dodge/index.html` — 우주 배경 장애물 피하기 게임
- `blink-catch/index.html` — 반응 속도 미니게임
- `.nojekyll` — GitHub Pages의 Jekyll 처리 방지

## 동작 방식
- 루트 `index.html`은 게임 목록과 진입 버튼을 보여주는 대시보드입니다.
- 각 게임은 자기 폴더 안의 `index.html`로 실행됩니다.
- 새 게임을 추가할 때는 `games/<slug>/index.html` 형태로 만들고, 대시보드의 배열에 카드만 추가하면 됩니다.

## GitHub Pages 배포
1. 이 `games/` 폴더를 저장소 루트 또는 Pages 대상 폴더에 둡니다.
2. GitHub 저장소의 Pages 설정에서 브랜치와 폴더를 지정합니다.
3. 배포가 완료되면 대시보드 URL이 메인 진입점이 됩니다.

## 로컬 확인
- 브라우저에서 `index.html`을 열면 대시보드가 바로 뜹니다.
- `orbit-dodge/`와 `blink-catch/` 링크는 각각의 게임으로 연결됩니다.
