


Thomas Erl的《SOA设计模式》中的3个模式
规范表述、元数据集中和规范版本控制
http://www.infoq.com/cn/articles/3-SOA-Design-Patterns-Thomas-Erl


版本通常是由数字标识的，它经常被注入在服务契约中，或者作为可读性的注解，或者作为技术性契约内容的扩展。

兼容性保证 —— 大版本号和小版本号用于描述兼容性。最常见的规则是大版本号的增加意味着服务契约的一个非向后兼容性的改变，而小版本号 的改变则代表着相后兼容的变更，因此，小版本号的增加就意味着服务消费者不会受到影响。

http://www.infoq.com/cn/articles/SOA-Design-Patterns-Thomas-Erl-2
当将版本号作为消息的一部分时，版本标识等同于格式指示器（Hohpe，Woolf）。