# 형식 맞추기

### 적절한 행 길이를 유지하라

**신문 기사처럼 작성하라**

- 소스 파일도 신문 기사와 비슷하게 작성한다. 이름은 간단하면서도 설명이 가능하게 짓는다.
이름만 보고도 올바른 모듈을 살펴보고 있는지 아닌지를 판단할 정도로 신경 써서 짓는다.
소스 파일 첫 부분은 고차원 개념과 알고리즘을 설명한다. 아래로 내려갈수록 의도를 세세하게 묘사한다.
마지막에는 가장 저차원 함수와 세부 내역이 나온다.

**개념은 빈 행으로 분리하라**

- 빈 행은 새로운 개념을 시작한다는 시각적 단서다. 코드를 읽어내려가다 보면 빈 행 바로 다음 줄에 눈길이 멈춘다.

**세로 밀집도**

- 줄바꿈이 개념을 분리한다면 세로 밀집도는 연관성을 의미한다.
즉, 서로 밀접한 코드 행은 세로로 가까이 놓여야 한다는 뜻이다.

**수직 거리**

1. 서로 밀접한 개념은 세로로 가까이 둬야 한다. 타당한 근거가 없다면 서로 밀접한 개념은 한 파일에 속해야 마땅하다.
이게 바로 protected 변수를 피해야하는 이유 중 하나다.

2. **변수 선언.** 변수는 사용하는 위치에 최대한 가까이 선언한다.

3. **인스턴스 변수.** 인스턴스 변수는 클래스 맨 처음에 선언한다. 변수 간에 세로로 거리를 두지 않는다.
잘 설계한 클래스는 많은 클래스 메서드가 인스턴스 변수를 사용하기 때문이다.

4. **종속 함수.** 한 함수가 다른 함수를 호출한다면 두 함수는 세로로 가까이 배치한다.
또한 가능하다면 호출하는 함수를 호출되는 함수보다 먼저 배치한다. 그러면 프로그램이 자연스럽게 읽힌다.
규칙을 일관적으로 적용한다면 독자는 방금 호출한 함수가 잠시 후에 정의되리라는 사실을 예측한다.

5. **개념적 유사성.** 어떤 코드는 서로 끌어당긴다.
개념적인 친화도가 높기 때문이다. 친화도가 높을수록 코드를 가까이 배치한다.

**세로 순서**

- 일반적으로 함수 호출 종속성은 아래 방향으로 유지한다. 다시 말해, 호출되는 함수보다 나중에 배치한다.
그러면 소스 코드 모듈이 고차원에서 저차원으로 자연스럽게 내려간다.




