OOP란?
==

OOP는 현실 세계를 프로그래밍으로 옮겨와 현실 세계의 사물들을 객체로 보고, 그 객체로부터 개발하고자 하는 특징과 기능을 뽑아와 프로그래밍하는 기법이다.<br>
OOP로 코드를 작성하면 재사용성과 변형가능성을 높일 수 있다.

### OOP의 5가지 설계 원칙
1. SRP(Single Responsibility Principle, 단일 책임 원칙): 클래스는 단 하나의 목적을 가져야 하며, 클래스를 변경하는 이유는 단 하나의 이유여야 한다.
2. OCP(Open-Closed Prionciple, 개방 폐괴 원칙): 클래스는 확장에는 열려 있고, 변경에는 닫혀 있어야 한다.
3. LSP(Liskov Substitution Principle, 리스코프 치환 원칙): 상위 타입의 객체를 하위 타입으로 바꾸어도 프로그램은 일관되게 동작해야 한다.
4. ISP(Interface Segregarion Principle, 인터페이스 분리 원칙): 클라이언트는 이용하지 않는 메소드에 의존하지 않도록 인터페이스를 분리해야 한다.
5. DIP(Dependency inversion Principle, 의존 역전 법칙): 클라이언트는 추상화(인터페이스)에 의존해야 하며, 구체화(구현된 클래스)에 의존해선 안되다.