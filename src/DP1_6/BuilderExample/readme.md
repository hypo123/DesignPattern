遇到多个构造器参数时要考虑使用建造者模式 [builder]

1.重载的构造函数
	使用多个重载的构造函数可以处理，但是当有许多参数时，客户端代码会很难写.
	
2.JavaBeans模式
	JavaBeans方式调用一个无参构造函数来创建对象，然后调用setter方法来设置每一个必要参数的值，以及每个相关的可选参数.
	JavaBeans方式的缺陷是，因为构造过程被分到了几个调用中，在构造过程中JavaBean可能处于不一致的状态.
	JavaBeans方式阻止了把类做成不可变的可能，这需要程序员付出额外的努力来确保它的线程安全.
	
3.建造者模式
	建造者模式即保证了重载的构造函数方式那样的安全性，也能保证JavaBeans方式那么好的可读性.

