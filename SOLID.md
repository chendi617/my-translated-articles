### S.O.L.I.D
This article is about the SOLID principles of object-oriented programming. For the fundamental state of matter, see [Solid](https://en.wikipedia.org/wiki/Solid). For other uses, see Solid (disambiguation).

In object-oriented computer programming, SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible and maintainable. It is not related to the GRASP software design principles. The principles are a subset of many principles promoted by American software engineer and instructor Robert C. Martin. Though they apply to any object-oriented design, the SOLID principles can also form a core philosophy for methodologies such as agile development or adaptive software development. The theory of SOLID principles was introduced by Martin in his 2000 paper Design Principles and Design Patterns,although the SOLID acronym was introduced later by Michael Feathers.

本文是关于面向对象编程的SOLID原则。如果是想看物质的基本状态，请看[Solid](https://en.wikipedia.org/wiki/Solid) 。其他使用，请看[Solid (disambiguation)](https://en.wikipedia.org/wiki/Solid_(disambiguation))

在面向对象软件编程中，SOLID是五个软件设计原则的助记缩写，旨在作出更难加易懂的，弹性的和可维护的软件设计。它和GRASP软件设计原则没有关系。这些原则是被美国软件工程师兼导师的Robert C. Martin提出的许多原则的一个集合。虽然他们被应用在一些面向对象设计中，SOLID原则也可以成为一些方法论的核心理念，比如想是敏捷开发和自适应软件开发。SOLID原则的理论是Martin在他的2000年的论文《设计原则与设计模式》中提出的，不过SOLID缩写是被Michael Feathers后来提出的。

### Concepts
#### Single-responsibility principle
A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
#### Open–closed principle
"Software entities ... should be open for extension, but closed for modification."
#### Liskov substitution principle
"Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.
#### Interface segregation principle
"Many client-specific interfaces are better than one general-purpose interface."
#### Dependency inversion principle
One should "depend upon abstractions, [not] concretions."

### 概念
#### 单一职责原则
一个类应该仅有一个单一的职责，更确切的说，仅对软件规范的一部分更改才能影响类的规范。
#### 打开-关闭原则
软件实体应该对扩展开放，对修改关闭。
#### 里斯科夫替换原则
“程序里的对象应该能够被其他子类的实例替换，而不改变程序的正确性“。在契约式编程里也可以看到。（design by contract可以拓展学习一下）
#### 接口隔离原则
“许多客户端专用接口好过于一个通用目的接口。“
#### 依赖倒转原则
一个类需要“依赖抽象，而不依赖具体”。
