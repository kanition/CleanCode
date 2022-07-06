# 类
1. 类的组织：Java中先写变量：公有静态变量、私有静态变量、私有实例变量，很少用共有变量，然后列出函数，公有函数在前，其调用的私有函数在后
2. 可以因为测试需要把需要访问的变量或函数设为保护型，但这是不得已的手段
3. 类要尽量小：单一职责原则：类应只有一种职责以及一种修改原因
4. 内聚：类方法应操作尽量多的类内变量，因为这意味着该方法与类的内聚性强
5. 维护内聚性：将大函数拆成小函数，就会需要把参数传给小函数，为了缩短形参表，就把这些参数升格为类内实例变量，为了避免类内变量过多降低内聚性，就从中拆分出新类
6. 为修改而组织；隔离修改
7. 开闭原则：对扩展开放，对修改封闭
8. 依赖倒置原则：类应依赖具体抽象而非细节