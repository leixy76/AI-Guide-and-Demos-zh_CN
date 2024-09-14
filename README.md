# 这是一个中文的 LLM 入门项目

> 回顾过去的学习历程，发现在深度学习这条道路上，吴恩达和李宏毅老师的视频分享为我提供了非常巨大的帮助，幽默风趣的讲课方式，直观简单的理论阐述，使得课程生动有趣。但总会有学弟学妹们最初烦恼于怎么去获取国外大模型的 API，虽然总会解决，但我还是想将这个槛给拿掉，毕竟第一次总有畏难情绪。
>
> 这里不会提供🪜的教程，也不会使用大模型平台自定义的接口，而是使用 OpenAI SDK，期望能够让你学到更通用的知识。我会以阿里云大模型平台所提供的 API 为例，带你从 API 走进 LLM。
> 非常建议搭配课程【生成式人工智能导论】进行学习。
>
> - [课程主页](https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php)
> - [视频 - Bilibili](https://www.bilibili.com/video/BV1BJ4m1e7g8)
>

简要介绍目录的内容：

- **Demos**
  
  所有的代码文件都将存放在其中，对应于序号。
  
- **assets**
  
  不需要关注这个文件夹，这里是 .md 文件用到的图片。
  
- [0. 阿里大模型API获取步骤](https://github.com/Hoper-J/LLM-Guide-and-Demos/blob/master/0.%20阿里大模型API获取步骤.md)

  将带你一步步的获取 API，如果是第一次注册，你需要进行一次身份验证（人脸识别）。

- [1. 初识LLM API：环境配置与多轮对话演示](https://github.com/Hoper-J/LLM-Guide-and-Demos/blob/master/1.%20初识LLM%20API：环境配置与多轮对话演示.md)

  这是一段入门的配置和演示，对话代码摘自阿里开发文档。

- [2. 简单入门：通过API与Gradio构建AI应用](https://github.com/Hoper-J/LLM-Guide-and-Demos/blob/master/2.%20简单入门：通过API与Gradio构建AI应用.md)

  指导如何去使用 Gradio 搭建一个简单的 AI 应用。对应课程镜像【HW3：以 AI 搭建自己的應用】。

- [3. 进阶指南：自定义 Prompt 提升大模型解题能力](https://github.com/Hoper-J/LLM-Guide-and-Demos/blob/master/3.%20进阶指南：自定义%20Prompt%20提升大模型解题能力.md)

  你将学习自定义一个 Prompt 来提升大模型解数学题的能力，其中一样会提供 Gradio 和非 Gradio 两个版本，并展示代码细节。对应课程镜像【HW4：Become an AI Hypnosis Master】。

  

目前的规划：

1. 将完全复现【生成式人工智能导论】这门课程的所有代码（画饼ing）具体：

   - 将其中的行为使用 OpenAI 库进行替换
   - 使用 ipywidgets 模拟 Colab 的交互
   - 以中文进行作业引导

   下一节预告：LLM微调。

2. ...