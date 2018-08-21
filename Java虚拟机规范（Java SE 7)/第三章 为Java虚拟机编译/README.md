# 为Java 虚拟机编译
* Java 虚拟机是为了支持Java 语言而的设计的。Oracle 的JDK 包括两部分内容：一部分是
将Java 源代码编译成Java 虚拟机的指令集的编译器，另一部分是用于Java 虚拟机的运行时环
境。理解编译器是如何与Java 虚拟机协同工作的，对编译器开发人员来说很有好处，同样也有助
于理解Java 虚拟机本身。





# 同步
* Java 虚拟机中的同步（Synchronization）基于进入和退出管程（Monitor）对象实现。

* Java 语言中，同步用的最多的地方可能是被synchronized 修饰的同步方法。同步方法
并是由方法调用指令读取运行时常量池中方法的ACC_SYNCHRONIZED 标志来隐式实现的。
monitorenter 和monitorexit 指令用于实现同步语句块