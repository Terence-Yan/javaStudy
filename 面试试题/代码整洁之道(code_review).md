#### 1.编码的SOLID原则
* 单一职责原则(Single Responsibility Principle, SRP)
```
一个类只承担一个职责，一个方法只承担一个职责，看问题的视角不同，职责的范围界定就可能不同。
```
* 开闭原则(Open-closed Principle)
```
该原则描述的是软件产品的质量目标：对扩展开放，对修改关闭；高内聚，低耦合
```
* 里氏替换原则(The Liskov Substitution Principle)
```
该原则是面向接口编程的具体体现，是在代码层面的具体指导。该原则告诉我们，软件开发时，接口的定义要职责单一、简洁，
保证子类在实现或扩展时，能够具备父类的所有功能，不能出现未实现功能或功能的“弱化”。也就是说，接口(父类)对外的
承诺，子类必须能够完全兑现。
```
* 接口隔离原则(Interface Segregation Principle)
```
该原则是面向接口编程的指导方针，要求在定义接口时，接口的职责要保持单一，声明的方法都尽量是子类必须要现实的，
否则编码时就可能违反里氏替换原则。
```
* 依赖倒置原则(Dependence Inversion Principle)
```
对于一个软件产品，如果从人的角度去看的话，可以分为开发者与使用者，该原则告诉我们在进行软件开发时，应尽量做到
具体实现依赖于接口，而不是具体实现完成后再去开发接口(或抽象出接口)，并且接口的定义应该是由“使用者”完成的，
或者说应该站在“使用者”的角度去定义接口。
```
###### 参考文章
* <a href="https://mp.weixin.qq.com/s/VLgSGx8tWYR2a_0IqRCyig" target="_blank">写了这么多年代码，你真的了解SOLID吗？</a>

#### 2.编码优秀实践

###### 参考文章
* <a href="https://mp.weixin.qq.com/s/FQisGVHFvoKQG26jBPeatw" target="_blank">可以提高千倍效率的Java代码小技巧</a>




