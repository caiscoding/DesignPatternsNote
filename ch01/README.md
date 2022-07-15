# 设计模式概述

## 什么是设计模式

简单地讲，<strong><font color="#2948ff">设计模式</font></strong>就是一种解决方案，它针对于系统服务设计中的常用场景。

设计模式是一种开发设计指导思想，对于实际的问题，不同的场景同一种设计模式有不同的实现方式，同一种场景不同开发者也可以有不同的实现方式。

## 设计模式产生的背景

“设计模式”这个概念最初是用于建筑领域设计中的。

1977 年，美国著名建筑大师、加利福尼亚大学伯克利分校环境结构中心主任克里斯托弗·亚历山大（Christopher Alexander）在他的著作《建筑模式语言：城镇、建筑、构造（A Pattern Language: Towns Building Construction）中提出了 253 种关于对城镇、邻里、住宅、花园、房间以及构造的模式。

1995 年，艾瑞克·伽马（ErichGamma）、理査德·海尔姆（Richard Helm）、拉尔夫·约翰森（Ralph Johnson）、约翰·威利斯迪斯（John Vlissides） 4 位作者合作出版了<strong><font color="#2948ff">《设计模式：可复用面向对象软件的基础》（Design Patterns: Elements of Reusable Object-Oriented Software）</font></strong>一书，将设计模式的概念推向程序开发中。一般我们以“四人组”（Gang of Four，GoF）代称这 4 为作者。

## 模式的四个基本要素

1. <strong><font color="#2948ff">模式名称（pattern name）</font></strong>：用于简单描述模式的问题、解决方案和效果。
2. <strong><font color="#2948ff">问题（problem）</font></strong>：描述何时使用该模式。
3. <strong><font color="#2948ff">解决方案（solution）</font></strong>：描述设计的组成成分、它们之间的相互关系以及各自的职责和协作方式。
4. <strong><font color="#2948ff">效果（consequences）</font></strong>：描述模式的应用效果以及使用模式要权衡的问题。

## 设计模式的种类

我们可以按照以下两条准则对模式进行分类：

1. <strong><font color="#2948ff">目的</font></strong>：模式是用来完成什么工作的。按目的准则分，可以分为 <strong><font color="#2948ff">创建型（Creational）</font></strong> 、 <strong><font color="#2948ff">结构型（Structural）</font></strong> 、 <strong><font color="#2948ff">行为型（Behavioral）</font></strong> 三种。
2. <strong><font color="#2948ff">范围</font></strong>：指定模式主要用于类还是对象。

<center>

表： 设计模式的分类

</center>

<table>
<tr>
<th colspan="2" rowspan="2">
</th>
<th colspan="3">
目的
</th>
</tr>
<tr>
<th>
创建型
</th>
<th>
结构型
</th>
<th>
行为型
</th>
</tr>
<tr>
<th rowspan="2">
范围
</th>
<th>
类
</th>
<td>
Factory Method（工厂模式）
</td>
<td>
Adapter（类）（适配器模式）
</td>
<td>

Interpreter（解释器模式）

Template Method（模板模式）

</td>
</tr>
<tr>
<th>
对象
</th>
<td>

Abstract Factory（抽象工厂模式）

Builder（建造者模式）

Prototype（原型模式）

Singleton（单例模式）

</td>
<td>

Adapter（对象）（适配器模式）

Bridge（桥接模式）

Composite（组合模式）

Decorator（装饰器模式）

Facade（外观模式）

Flyweight（享元模式）

Proxy（代理模式）

</td>
<td>

Chain of Responsibility（责任链模式）

Command（命令模式）

Iterator（迭代器模式）

Mediator（中介者模式）

Memento（备忘录模式）

Observer（观察者模式）

State（状态模式）

Strategy（策略模式）

Visitor（访问者模式）

</td>
</tr>
</table>