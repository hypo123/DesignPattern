桥接模式	[结构型模式]
抽象化角色(Abstraction)
修正抽象化角色(RefinedAbstraction)
实现化角色(Implementor)
具体实现化角色(ConcreteImplementor)

继承是一种强耦合,它在一开始便把抽象化角色和实现化角色的关系绑定了,使得两个层次之间相互限制,无法独立地演化.

桥接模式将两个角色之间的继承关系改为聚合关系,就是将它们之间的强关联改换成弱关联。