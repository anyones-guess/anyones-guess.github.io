---
layout: default
title: 01. SOLID
has_children: false
parent: Terminology
published_date: 2024-02-15
last_modified_date: 
nav_order: 1
---



{: .no_toc }

<!-- ## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc} -->

---
## Single responsibility principle 
단일 책임 원칙
- 한 클래스는 하나의 책임만. 
- 하나의 책임이라는 것은 매우 모호. 
- 변경이 있을 때 파급 효과가 적으면 SRP 를 잘 따른 것

---
## Open/closed principle
개방-폐쇄 원칙
- 소프트웨어는 확장에는 열려 있으나, 변경에는 닫혀 있어야 함

---
## Liskov substitution principle
리스코프 치환 원칙
- 프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다.
- 자동차 인터페이스의 핸들은 방향을 조정하는 기능. 핸들이 방향이 아닌 속도를 조정하도록 구현하면 LSP 위반

---
## Interface segregation principle
인터페이스 분리 원칙
- 인터페이스 여러 개가 범용 인터페이스 하나보다 나음
- 자동차 인터페이스를 운전 인터페이스, 정비 인터페이스로 분리하면, 정비 인터페이스가 변하더라도 운전자 클라이언트에 영향을 주지는 않는다. 

---
## Dependency inversion principle
의존관계 역전 원칙
- 구현 클래스에 의존하지 말고, 인터페이스에 의존
- 클라이언트가 인터페이스에 의존해야 유연하게 구현체를 변경할 수 있다.
