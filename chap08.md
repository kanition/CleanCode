# 边界
1. 使用第三方代码时：避免到处使用第三方API或将其作为返回或传入类型，否则牵一发而动全身，可通过封装它们限制其（对于本系统）多余的功能
2. 探索和学习边界：通过编写测试来验证我们对第三方API的理解，而不是在正式使用时来经历bug；它还利于我们检测API的变动和迁移新版本
3. 使用不存在的代码：预先定义接口代替还不能立即用上的API