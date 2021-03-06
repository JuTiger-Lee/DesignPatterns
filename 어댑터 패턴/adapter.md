# 어댑터 패턴(Adapter Pattern)

- 한 클래스의 인터페이스를 클라이언트에서 사용하고자 하는 다른 인터페이스로 변환한다.
- 어댑터를 이용하면 인터페이스 호환성 문제 때문에 같이 쓸 수 없는 클래스들을 연결해서 쓸 수 있다.

## 클래스 어댑터

- 클래스 어댑터는 Java에서는 구현이 불가능하다, 클래스 어탭터는 어대텁가 타겟 class, 어댑티 class 모드위 서브클래스를 만든다.
- 즉 타겟 class, 어댑티 class를 다중상속을 받아서 구현한다.
- 이렇게되면 서브클래스이기 때문에 행동을 오버라이드 할 수 있다.

## 객체 어댑터

- 객체 어댑터는 타겟 인터페이스를 구현하고 어댑티 클래스를 상속이 아닌 구성을 통해 구현을 한다.
- 구성으로 기능을 구현하기 때문에 유연성이 좋다.

## 데코레이터, 어댑터, 퍼사드 차이

### 데코레이터

- 한 인터페이스를 다른 인터페이스로 변환

### 어댑터

- 인터페이스는 바꾸지 않고 책임(기능)만 추가

### 퍼사드

- 인터페이스를 간단하게 바꿈
