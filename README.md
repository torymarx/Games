# Blink Catch — GitHub Pages 배포용

이 폴더는 GitHub Pages에 바로 올릴 수 있는 정적 버전입니다.

## 포함 파일
- `index.html` — 단일 파일 게임

## 동작
- 30초 동안 랜덤으로 나타나는 구슬 클릭
- 클릭할수록 더 작아지고 더 빨라짐
- 최고 점수는 브라우저 로컬 저장소에 저장
- Enter 시작 / Esc 일시정지

## GitHub Pages 배포 방법
1. 이 폴더의 `index.html`을 저장소 루트 또는 `docs/` 폴더로 복사
2. GitHub 저장소에서 Pages 설정을 열기
3. Source를 `Deploy from a branch`로 설정
4. Branch를 `main` + `/root` 또는 `main` + `/docs`로 지정
5. 저장 후 잠시 기다리면 URL이 생김

## 로컬 확인
브라우저에서 `index.html`을 직접 열어도 바로 실행됩니다.
