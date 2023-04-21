# 영화 미션

## 3단계

### 미션 목표

사용자는 영화 예매 시스템에서 등급별 좌석을 선택할 수 있다.

### 요구 사항

- [x] `TableLayout` 사용
- [ ] 기능 요구 사항에 대한 UI 테스트

### 기능 목록

- [x] 사용자는 인원/날짜 선택 후에 좌석을 고를 수 있다.
- [x] 좌석은 총 5행 4열로 구성되어 있고 각 행은 알파벳, 열은 숫자로 표현한다.
- [x] 좌석을 선택하면 배경색이 바뀐다
- [x] 좌석을 선택하면 하단에 할인정책과 좌석 등급을 고려한 최종 가격이 표시된다.
- [x] 선택된 좌석을 재선택하면 선택이 해제된다.
- [x] 좌석 정책은 다음과 같다.
1, 2행은 B등급, 보라색 글자로 표시한다. (10,000원)
3, 4행은 S등급, 초록색 글자로 표시한다. (15,000원)
5행은 A등급, 파란색 글자로 표시한다. (12,000원)
- [x] 최종 예매를 확인하는 다이얼로그가 표시되고 배경을 터치해도 사라지지 않아야 한다.

## 4단계

### 미션 목표

사용자는 영화 목록에서 광고를 볼 수 있다.

###

- [ ] list view를 recycler view로 교체

### 기능 목록

- [ ] 영화 목록에 영화가 세 번 노출될 때마다 광고가 한 번 노출된다.
- [ ] 영화 목록의 요소는 10,000개까지 추가될 수 있다.