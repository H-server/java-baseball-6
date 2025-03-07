# 자바 테스트

## 단위 테스트(Unit Test)

- 하나의 모듈을 기준으로, **독립적으로** 진행되는, 가장 작은 단위의 테스트
- 일반적으로 실무에서 테스트 코드를 작성한다고 하면 대부분 단위 테스트를 의미함.
- 모듈: 프로그램에서 작동하는 하나의 기능 또는 메소드
- 장점: 빠르게 리팩토링할 수 있어 효율, 안정성을 확보할 수 있음.
- stub: 테스트하고자 하는 객체가 다른 객체와 메시지를 주고 받는 경우,
  다른 객체 대신에 가짜 객체(mock object)를 주입하여 정해진 리턴값을 반환

## 통합 테스트(Integration Test)

- 모듈을 통합하는 과정에서 모듈 간의 호환성을 확인하기 위해 수행되는 테스트

## 단위 테스트 라이브러리

- JUnit5: 자바 단위 테스트를 위한 테스팅 프레임워크
    - @Test: 해당 메소드가 단위 테스트임을 명시하는 어노테이션(주석)
- AssertJ: 자바 테스트를 돕기 위해 다양한 문법을 지원하는 라이브러리

## 테스트 코드 구조

- given-when-then 구조로 흔히 작성함.

## JUnit


