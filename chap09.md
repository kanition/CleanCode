# 单元测试
1. 测试驱动开发（TDD）三原则：除非能让失败的单元测试通过，否则不要编写任何产品代码；只编写刚好导致失败的单元测试（包括编译失败）；只编写刚好使得一个失败的单元测试通过的产品代码
2. 测试代码应和生成代码一样干净，一样高标准
3. 干净的测试代码有助于提升系统的灵活性、可维护性、可复用性等
4. 干净的测试最重要的是可读性：清晰、简单、信息丰富，用最少的表达式充分交代内容
5. 测试三段式：构建测试数据，操作测试数据，检查测试数据
6. 测试代码也是可以封装基本的API来提升简洁性、易用性
7. 双重标准：测试和生成环境有别，所以对测试代码的效率要求可能不同，但这不意味着放松对简洁性的要求
8. 每个测试只有一个断言：不必这么苛刻，但确实少点更好
9. 每个测试应只测试一个概念或规则
10. FIRST原则：运行快（fast）、互相独立（independent）、可复现（repeatable）、自我验证（指输出是否通过的布尔值）（self-validating）、及时编写（timely）
