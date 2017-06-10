# javathread
javathread笔记

java 线程创建方法

方法1：创建一个集成Thread类的类 ，在该类中重写run（）方法。创建该类的实例。调用该实例的start()方法启动线程，运行run()方法。
方法2：创建一个实现runnable接口的类，在该类中重写run()方法。创建该类的实例，并将该实例作为参数实例化Thread类。该thread类调用start()方法启动线程，
运行run()方法。
