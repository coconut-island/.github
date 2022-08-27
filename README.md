# Coconut Island

![images](https://avatars.githubusercontent.com/u/104977332?s=200&v=4)

Coconut Island 是一个自发的开源爱好者组成的社区，目前成员是杭州各公司在职的Web全栈以及AI算法工程师。

目前在做一个在PC端CPU运行的人脸平台CNIFace，包括算法推理部分、Web后端以及Web前端，
目的是想向别人介绍，人脸平台的实现流程是如何具体实现的。

CNIFace算法推理部分选用TVM LLVM做为推理引擎，原因是因为Abel Lee所在的公司的技术选型是用TVM作为前端。

选用CPU端，没有选择GPU作为开始，是因为GPU端开发确实环境受限，第一版本的场景也用不到GPU那么大的算力。

CNIFace Web部分，选用的是Java Spring全家桶以及前端框架react，
是因为Abel Lee之前做Web全栈的时候对这套技术栈比较擅长。
选用antdpro是因为纯粹偷懒，想要快速集成开发。

如果CNIFace如果能帮助到你，那请点个start再走吧。
