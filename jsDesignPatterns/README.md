《JavaScript设计模式》
===

##模式
###什么是模式
模式是一个可复用的解决方案，可用于解决软件设计中的常见问题。它有三大好处：
1. 模式是已验证的解决方案
2. 模式很容易被复用
3. 模式富有表达力

###优秀的模式
优秀的模式应当可以执行以下操作：
1. 解决特殊问题
2. 没有显而易见的解决方案
3. 描述经过验证的概念
4. 描述一种关系

##反模式
###什么是反模式
反模式是：
- 描述一种针对某个特定问题的不良解决方案，该方案会导致糟糕的情况发生
- 描述如何摆脱前述的糟糕情况以及如何创造好的解决方案

如果一个完美的设计应用于错误的上下文中，那么它可能使用反模式

###JavaScript中的反模式示例
1. 全局上下文中定义大量变量污染全局命名空间
2. 向setTimeout或setInterval传递字符串，而不是函数，触发`eval()`
3. 修改Oject的原型
4. 以内联形式使用JavaScript
5. 使用document.createElement等原生DOM方法更合适的情况下，去使用document.write

##设计模式的类别
###创建型设计模式
专注于处理对象创建机制，以合适给定情况的方式来创建对象。这种设计模式包括：
- Constructor 构造器
- Factory 工厂
- Abstract 抽象
- Prototype 原型
- Singleton 单例
- Builder 生成器

###结构型设计模式
结构型设计模式与对象组合有关，通常可以用于找出在不同对象之间建立关系的简单方法。这种模式有助于确保系统某一部分改变时，不会影响到整体结构。同时在改变后能够较好地重组。这种设计模式包括：
- Decorator 装饰者
- Facade 外观
- Flyweight 享元
- Adapter 适配器
- Proxy 代理

###行为设计模式
专注于改善或简化系统中不同对象之间的通信，这种设计模式包括：
- Iterator 迭代器
- Mediator 中介者
- Observer 观察者
- Visitor 访问者
