# 자동차 경주

## 기능 목록
**경주 - Race**
- [ ] 경주 시작전 상황을 세팅한다. - `init()` 
- [ ] 세팅을 마치면 경주를 시작한다. - `start()` 
- [ ] 우승자가 발생 여부를 확인한다 - `checkWinner()` 

**입출력 - Race**
- [ ] 자동차의 이름을 입력 받아 저장한다. - `getCarNames()`
- [ ] 몇 번의 이동을 할 것인지 입력 받는다. - `getMoveCount()`
- [ ] 현 경주 상황을 출력할 수 있다. - `showCurrentRace()`
- [ ] 우승자가 결정나면 우승자 목록을 출력한다 - `showWinner()`

**자동차 - Car**
- [ ] 자동차는 조건에 따라 움직일 수 있어야 한다. - `move()`
- [ ] 자동차의 현 상황을 반환할 수 있어야 한다. - `status()`

**예외처리 - ExceptionHandler**
- [ ] 잘못된 입력에 대해 `IllegalArgumentException`을 발생시킨다. - `InputException()`