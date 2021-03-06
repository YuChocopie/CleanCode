# CleanCode

## 들어가며

프로그램을 짜다 보면, 코드를 쓰는 시간보다 코드를 읽는 시간이 훨씬 더 많다는 사실을 알고 있다면, 이 책에서 제시하는 보이스카우트 규칙을 다른 모든 규칙에 앞서 특히 신경을 써서 봐야 한다.
보이스카우트 단원들에게 야영장에 들어올 때보다 나갈 때 더 깨끗한 상태로 만들 의무가 있다면, 우리 개발자들에게는 체크아웃해 코드를 꺼낼 때보다 체크인해서 코드를 넣을 때 더 깨끗한 상태로 만들어야 할 의무가 있다.

**훌률한 소프트웨어 기법**

훌륭한 소프트웨어 기법은 집중, 침착, 사고라는 규율을 요구한다. 행동이 전부가 아니다. 무작정 설비를 돌려 제품만 찍어낸다고 다가 아니다. 5S 철학은 다음 개념으로 이뤄진다.

1. 정리 또는 조직 : 적절한 명명법 등과 같은 방법을 사용해 무엇이 어디에 있는지 알아야 한다.
2. 정돈 또는 잔정함 : "물건마다 모두 제자리가 있다"라는 속담이 있다. 코드는 누구나 예상하는 위치에 있어야 한다. 그렇지 않으면 다시 정돈해 누구나 예상하는 위치로 옮기기 바란다.
3. 청소 또는 정리 : 작업 공간에서 배선이다 기름이나 부스러기나 쓰레기는 치운다. 과거 이력이나 미래 바람을 기억한 주석 혹은 주석으로 처리한 코드는 어떻게 처리하라고? 제거하기 바란ㄷ.
4. 청결 또는 표준화 : 작업 공간을 청소하는 방식에 그룹이 동의한다. 그룹 내에서 일관적인 구현 스타일과 기법의 필요성을 알아야 한다.
5. 생활화 또는 규율 : 관례를 따르고, 자기 작품을 자주 돌아보고, 기꺼이 변경하는 규율을 뜻한다.

### 읽기 좋은 코드는 돌아가는 코드만큼이나 중요하다.

### 제조업이란 메타포에서 재작업은 비용을 뜻하니만 소프트웨어 설계에서 재작업은 가치를 가져온다.

깨끗한 코드를 작성하는 방법은 배우기 어렵다. 단순히 원칙과 패턴을 안다고 깨끗한 코드가 나오지 않는다. 고생을 해야 한다. 스스로 연습하고 실패도 맛봐야 한다.
남들이 시도하다 실패하는 모습도 봐야 한다. 그들이 넘어지고 일어서는 모습도 봐야 한다. 결정을 내리느라 고민하는 모습, 잘못된 결정으로 대가를 치르는 모습도 봐야 한다.