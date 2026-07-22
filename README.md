# healpan-google-blog-data

힐링팬더 놀이공간의 Blogger 픽업 카드 데이터 저장소입니다.

## 파일 구조

- `pickup-cards.json`: 카드 일정, 이름, 게임, 이미지 및 표시 순서
- `images/`: 카드용 WebP 이미지

카드는 `start` 시각부터 표시되고 `end` 시각에 자동으로 숨겨집니다. 날짜에는 한국 시간 오프셋 `+09:00`을 사용합니다. `order` 값이 낮을수록 먼저 표시됩니다.
