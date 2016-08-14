# OpenStack-Knowledge-Map
OpenStack  知识图谱！

# 缘由

OpenStack 从来就不是一个人的事，尤其是在商业的环境中，无论是前期的Poc功能验证、还是后期的交付、性能测试等。涉及的知识面太广，需要分工协作，需要一个完整的团队来共同交付！

那么既然需要分工，就得列出所涉及到的知识点，其实就是具体到需要掌握哪些项目，实际操作哪些部分。

其实，我更多的想法是，每一个知识块都有最好的文档链接。比如说到Ubuntu操作系统部分，就直接定位到[Ubuntu官方的服务器配置指南](https://help.ubuntu.com/lts/serverguide/serverguide.pdf)。

我想灵感来自于O'Reilly 当年对于Linux进阶的图书系列。

# 为什么选择使用 Graphivz 来描绘 此知识图谱？

因为有源码可以控制。

不服来战！


# 编译


```
dot -Tpng openstack_knowledge_map.dot -o openstack_knowledge_map.png
```

# 参与
