 react components 从创建到消失的状态和属性
![](component.png)

这个重新渲染的过程不一定会改变这个component的dom节点，react会把这个component的当前statte和最近一次statue对比，只有当status 确实发生的改变，并且印象到了dom结构的时候，react才会去改变对应的dom结构
![](component-1.png)

![](component-2.png)
![](component-3.png)
#### 什么是hook函数



![](component-4.png)

下面这段代码的执行效果是：init－will－did
![](component-5.png)

initstate的作用如下：
![](component-6.png)

state是可变的
