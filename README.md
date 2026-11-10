# 청송애플팜 주문 페이지

경북 청송 청송애플팜의 모바일 주문 안내 페이지입니다. GitHub Pages로 서비스합니다.

## 내용 고치는 법

`index.html` 아래쪽의 `CONFIG` 부분만 고치면 됩니다.

- 가격: `groups` 안의 `price` 숫자
- 판매 전 상품: `price: null` 이면 "준비 중"으로 표시
- 품절: 상품에 `soldout: true` 추가
- 주문 문자를 받는 번호: `smsPhone`
- 입금 계좌: `bank`
- 대표 사진: `images/apple.jpg` 파일을 올리면 자동 표시
