# 낙찰! 우리집 — 소개 페이지

경매로 가구를 사고, 집을 꾸며 코인을 모으는 2~4인 보드게임 **「낙찰! 우리집」** 소개 웹페이지입니다.

👉 https://lee-ye-eun.github.io/WinningBidMyHouse/

- 이야기 · 게임 방법(차례 4단계) · 배치 규칙(초록/빨간 칸) 미니 데모 · 텃밭 카드
- 카드 갤러리 45장(가격별 필터, 눌러서 크게 보기) · 게임 종료와 점수 · 룰북 12쪽 미리 보기 + A4 PDF

빌드 도구 없이 `index.html` 한 장과 `img/`, `files/`로 이루어져 있고, `main`에 push하면 GitHub Actions(`.github/workflows/pages.yml`)가 GitHub Pages로 배포합니다.

로컬에서 보기:

```bash
python3 -m http.server 8123
```
