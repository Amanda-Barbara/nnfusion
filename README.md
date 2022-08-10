# `nnfusion`框架源码解读
* `NNFusion`能够将现有的模型编译为对应设备的可高效运行的源码，同时支持用户自行替换内核实现或自动从外部导入高性能的内核实现。为了方便地与现有的代码库和`GPU`程序设计模型兼容，`NNFusion`采用的是源代码转换的方式，而不是像`TVM`、`Tensor Comprehension`一样定义新的计算抽象需要用户提供算子的计算逻辑。
## 关键字搜索
* `dnn compiler`、`tensor compiler`、`operator compiler`、`deeplearning compiler system`、`adavanced persistent thread`
## 参考链接
* 1 [深度学习编译框架](https://www.msra.cn/zh-cn/news/features/osdi-2020-rammer)
* 2 [快速高效的深度学习算子编译器](https://www.msra.cn/zh-cn/news/features/osdi-2022)
* 3 [深度学习编译系统概述](https://zhuanlan.zhihu.com/p/540332645)
* 4 [cuda persistent thread](https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html)




