# ncnn

---

ncnn 是一个为手机端极致优化的高性能神经网络前向计算框架。ncnn 从设计之初深刻考虑手机端的部属和使用。无第三方依赖，跨平台，手机端 cpu 的速度快于目前所有已知的开源框架。基于 ncnn，开发者能够将深度学习算法轻松移植到手机端高效执行，开发出人工智能 APP，将 AI 带到你的指尖。ncnn 目前已在腾讯多款应用中使用，如 QQ，Qzone，微信，天天P图等。

ncnn is a high-performance neural network inference computing framework optimized for the mobile platform. ncnn is deeply considered of the deployment and uses on mobile phones from the beginning of the design. ncnn does not have third party dependent, it is cross-platform, and runs faster than all known open source framework on mobile phone cpu. Developers can easily deploy deep learning algorithm models to the mobile platform by using the efficient ncnn implementation, create intelligent APP, and bring the artificial intelligence to your fingertips. ncnn is currently being used in many Tencent applications, such as QQ, Qzone, WeChat, Pitu and so on.

---

### 功能概述

* 支持卷积神经网络，支持多输入和多分支结构，可计算部分分支
* 无任何第三方库依赖，不依赖 BLAS/NNPACK 等计算框架
* 纯 C++ 实现，跨平台，支持 android ios 等
* ARM NEON 汇编级良心优化，计算速度极快
* 精细的内存管理和数据结构设计，内存占用极低
* 支持多核并行计算加速，ARM big.LITTLE cpu 调度优化
* 整体库体积小于 500K，并可轻松精简到小于 300K
* 可扩展的模型设计，支持 8bit 量化和半精度浮点存储，可导入 caffe 模型
* 支持直接内存零拷贝引用加载网络模型
* 可注册自定义层实现并扩展
* 恩，很强就是了，不怕被塞卷 QvQ

### Features

* Support convolution neural network, support multiple input and multi-branch structure, can calculate part of the branch
* No third-party library dependent, do not rely on BLAS / NNPACK or other computing framework
* Pure C ++ implementation, cross-platform, support android ios and so on
* ARM NEON assembly level of careful optimization, the calculation speed is extremely fast
* Sophisticated memory management and data structure design, very low memory footprint
* Support multi-core parallel computing acceleration, ARM big.LITTLE cpu scheduling optimization
* The overall library size is less than 500K, and can be easily reduced to less than 300K
* Extensible model design, support 8bit quantization and half-precision floating point storage, can import caffe model
* Support direct memory zero copy reference load network model
* Can be registered with custom layer implementation and extented
* Well, it is strong, not afraid of being stuffed with 卷   QvQ

---

### License

BSD 3 Clause

