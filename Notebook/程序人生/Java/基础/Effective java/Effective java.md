## 第一章 引言
## 第二章 创建和销毁对象
### 第一条：用静态工厂方法替代构造器
#### 1.1 概念
返回类的实例的静态方法
#### 1.2 示例
```java
public static Boolean valueOf(boolean b) {
	return b ? Boolean.TRUE : Boolean.FALSE;
}
```
#### 1.3 优点
1. 静态工厂方法与构造器不同的第一大优势在于，它们有名称 。
5. 