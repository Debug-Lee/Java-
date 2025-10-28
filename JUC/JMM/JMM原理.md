## happens-before 和 JMM 什么关系？
happens-before 与 JMM 的关系用《Java 并发编程的艺术》这本书中的一张图就可以非常好的解释清楚。
JMM规定-JMM实现-程序员遵守规范
<img width="1302" height="1020" alt="image" src="https://github.com/user-attachments/assets/f8eeed44-f42e-4fc9-b97e-0949476387a1" />


## JMM原理
你可以把 JMM 看作是 Java 定义的并发编程相关的一组规范，除了抽象了线程和主内存之间的关系之外，其还规定了从 Java 源代码到 CPU 可执行指令的这个转化过程要遵守哪些和并发相关的原则和规范，其主要目的是为了简化多线程编程，增强程序可移植性的。
