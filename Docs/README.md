## 기능 목록 작성
- Car 클래스
  - 자동차의 이동횟수를 저장하는 변수 선언
- 게임시작
    - Car 클래스에 자동차 이름(자동차 이름은 쉼표로 구분하고 5자 이하만 가능)과 시도 횟수 입력받는다. - mallang.missionutils.Console의 readline()
    - 시도 횟수가 숫자가 아닐 경우 ‘IllegalArgumentException’ 예외 발생시키고 ‘[ERROR] 시도 횟수는 숫자여야 한다.‘ 출력
    - 오류가 없을 경우 각각의 자동차 객체를 리스트에 저장
- 예외 발생 시 해당 부분부터 다시 입력받기
- 무작위 숫자 구하기 - mallang.missionutils.Randoms의 pickNumberInRange()
    - 무작위로 0 ~ 9 사이의 값을 구한다.
    - Car 클래스 내 이동횟수 저장
- 전진하기
  - 무작위의 값이 4 이상일 경우 전진 
- 중간값 출력하기
  - 자동차 이름과 함께 ‘-’로 무작위 수만큼 입력된다.
- 우승자 판단하기
  - 누적 횟수 비교해서 가장 큰값 찾기
- 우승자 출력하기
  - 단독 우승자의 경우
  - 공동 우승자의 경우 (우승자 여러명일 경우 ‘,’로 구분)

## 과제최종제출 질문
피드백을 반영해서 책임을 분리해보고 구현하지 않은 부분을 구현해보았습니다.
해당 부분들을 구현했지만 제대로 실행되도록하는 방법에 대한 어려움이 있습니다.