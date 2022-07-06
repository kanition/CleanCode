# 系统
1. 构建系统与使用系统分离：软件系统的启动过程应与运行时逻辑分开
2. 在`main`中分离构造与运行，先构造好需要的所有对象，再传给应用函数，应用函数不再操心初始化问题
3. 依赖注入：对象不应负责实例化其依赖项，而应将其交给另一个机制，通常是`main`或特殊容器
4. 扩展：若保持对分离性的关注，软件的架构是可以逐渐扩展的
5. *略去部分关于Java的看不懂的内容*
6. 测试驱动的系统架构（*看不懂*）
7. 优化决策：晚点再做决定
8. 在标准明显提供价值时巧妙地利用它
9. 系统需要特定域的语言