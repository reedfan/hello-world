1.序列化的两种方式
 serilizable      要想某个字段不被序列化   用transient修饰（静态变量不会被序列化）
 2.Externalizable  若实现的是Externalizable接口，则没有任何东西可以自动序列化，需要在writeExternal方法中进行手工指定所要序列化的变量，这与是否被transient修饰无关
 
 匿名内部类
 
