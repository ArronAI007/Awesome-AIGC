# Awesome-AGI

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ArronAI007)](https://github.com/anuraghazra/github-readme-stats)

## 技术交流

欢迎加入AIGC技术交流群，与AI领域专家和各行各业的AIGC爱好者一起交流技术理论与行业信息！不管你是学术界还是工业界实践者或爱好者，都欢迎加入群体！

| 交流群二维码                    | 拉你入群(备注AIGC-github)  |
| ------------------------------- | :------------------------: |
| ![Arron](https://i.postimg.cc/PqFvY1kW/AIGC-group.jpg) | ![Arron](https://i.postimg.cc/QMqj1DGc/Arron.jpg) |

## Table of Context
- [LLM 体验效果](#LLM-体验效果)
- [LLM Agent](#LLM-Agent)
- [LLM DataSet](#LLM-DataSet)
- [LLM LangChain](#LLM-LangChain)
- [LLM Model List](#LLM-Model-List)
- [LLM Open Tool](#LLM-Open-Tool)
  - [LLM Fine Tune](#LLM-Fine-Tune)
  - [LLM Deployment](#LLM-Deployment)
- [LLM Prompt Engineering](#LLM-Prompt-Engineering)

## LLM 体验效果

| Model_A| Model_B | Blog |
| --- | --- | --- |                                                                                                                     
| 360智脑 | 讯飞星火 | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486609&idx=2&sn=7fedb8ab37588d43968fdec2d7e5fcdd&chksm=ced54f75f9a2c663b9a2671f2548e2940730735605356cc0ffe72bc737470136a40032c80bfe&token=1282379489&lang=zh_CN#rd)|
| 阿里通义千问 | 讯飞星火 | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486534&idx=1&sn=6f36d41b618790cba62e63eb25bb033b&chksm=ced54fa2f9a2c6b4a901528f87a7e74628dfd79d835f4cdea1ee4dea442f339adfd2736b2305&token=1282379489&lang=zh_CN#rd)|
| Bard | Bing_VS_ChatGPT | [对比效果](https://www.theverge.com/2023/3/24/23653377/ai-chatbots-comparison-bard-bing-chatgpt-gpt-4)|
| baichuan-53B | ChatGLM-6B | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247487325&idx=1&sn=561cb8b09c37ccfe0ed1f73de04b1db6&chksm=ced54cb9f9a2c5af30ac3d134086c955ac240f452cad0ab2b3708bc3cc09ef5b662b831c7d62&token=293446899&lang=zh_CN#rd)|
| 文心一言 | Bard | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486260&idx=1&sn=a41224fee7ed4cb4a48eb40a420d7479&chksm=ced548d0f9a2c1c6f4930f30447468f9f01bb2af6031368e302b13a6354fc4bca6636e3b297e&token=666852558&lang=zh_CN#rd)|
| 文心一言 | Baize-7B | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486317&idx=1&sn=ea3cc745d2991b8c657325392ce68f71&chksm=ced54889f9a2c19f3c2f85d8d7af7fff366027f79d1f4a5b2c650fea1b5dee9efde0b7c992ca&token=1173964254&lang=zh_CN#rd)|
| 文心一言 | OpenAssistant | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486413&idx=2&sn=3816e5a4bccceee5e2af868166b18897&chksm=ced54829f9a2c13fb787b7a7e3c2aa0799eb7ff6d124f6847349346146900e05684ceb8cc7f7&token=1282379489&lang=zh_CN#rd)|
| 文心一言 | ChatGLM-6B | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486081&idx=2&sn=fd87305419158d66dd4b05b57bee1324&chksm=ced54965f9a2c073ba1badfedbc6610036455cd769a3c8ee3445f7fbff9364b5624091be9914&token=666852558&lang=zh_CN#rd)|
| 文心一言 | GPT-4 | [对比效果](https://mp.weixin.qq.com/s/l1pTPlohMmiYEMc4x6QKhw)|
| 文心一言 | GPT-4实测 | [对比效果](https://mp.weixin.qq.com/s/uO8N3RpcrYU8rV1RkwBxzQ)|
| 文心一言 | 讯飞星火 | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247486490&idx=1&sn=c8d756f7f26a4e35f8b67ae485efabce&chksm=ced54ffef9a2c6e8d66f8b744d6af524e320d5aec384d142621cee53fd2150f2c7db1fa7596a&token=1282379489&lang=zh_CN#rd)|
| GPT4 | ChatGPT | [对比效果](https://mp.weixin.qq.com/s?__biz=Mzg3NDIyMzI0Mw==&mid=2247485952&idx=2&sn=e54a62e358bf7aee3c007d59600fd452&chksm=ced549e4f9a2c0f2868eb8877c14fbe287a469e63b09774cefcb9edc4c0601016f6d36561973&token=666852558&lang=zh_CN#rd)|
| GPT4 | Claude2 | [对比效果1](https://mp.weixin.qq.com/s/dj2_WlWVpGwYsa8kO-GRFQ)，[对比效果2](https://mp.weixin.qq.com/s/Xo3XXQ5zYPmDxBYivhBYqA)|

## LLM Agent

| Description| Paper | Code | Blog |
| --- | --- | --- | --- |  
| AgentGPT |  | [AgentGPT Code](https://github.com/reworkd/AgentGPT) | [AgentGPT Chat](https://agentgpt.reworkd.ai/zh)，[AgentGPT docs](https://docs.reworkd.ai/introduction) |  
| AI Legion |  | [AI Legion Chat](https://github.com/eumemic/ai-legion) |  |  
| AutoGPT |  | [AutoGPT Code](https://github.com/Significant-Gravitas/Auto-GPT) | [AutoGPT docs](https://docs.agpt.co/setup/) ，[AutoGPT blog](https://generativeai.pub/complete-guide-to-setup-autogpt-revolutionize-your-task-automation-with-gpt-4-39eda5a85821?gi=ea5c40bac6fd) |  
| BabyAGI |  | [BabyAGI Code](https://github.com/yoheinakajima/babyagi) | [BabyAGI docs](https://babyagi.org/) |  
| CAMEL |  | [CAMEL Code](https://github.com/camel-ai/camel) | [CAMEL Chat](http://agents.camel-ai.org/)，[CAMEL docs](https://www.camel-ai.org/) |  
| Do Anything Machine |  |  | [Do Anything Machine Chat](https://www.doanythingmachine.com/) |  
| Generative Agents | [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) | [GPTRPG Code](https://github.com/dzoba/gptrpg) |  | 
| Godmode |  |  | [Godmode Chat](https://godmode.space/) |  
| GPT-Engineer |  | [GPT-Engineer Code](https://github.com/AntonOsika/gpt-engineer) |  |   
| HuggingGPT |  | [HuggingGPT Code](https://github.com/microsoft/JARVIS) | [HuggingGPT Chat](https://huggingface.co/spaces/microsoft/HuggingGPT) |  
| MetaGPT |  | [MetaGPT Code](https://github.com/geekan/MetaGPT) |  | 
| NexusGPT |  |  | [NexusGPT Chat](https://nexus.snikpic.io/) |  
| Toolformer | [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/pdf/2302.04761.pdf) |  | [Toolformer blog](https://www.sensorexpert.com.cn/article/194585.html) |  

## LLM DataSet

DataSet目录会介绍更多关于大模型数据集方面的事情，比如开源的数据集下载地址或者一些大模型pre-trained、SFT以及RLHF的数据处理，请参考[DataSet](https://github.com/ArronAI007/Awesome-AGI/tree/main/DataSet/README.md)

## LLM LangChain

LangChain目录会介绍关于LangChain的相关笔记和课程，请参考[LangChain](https://github.com/ArronAI007/Awesome-AGI/tree/main/LangChain/README.md)

## LLM Model List

Model List目录会对介绍baichuan、ChatGLM和LLaMA模型及其扩展模型，并且会对目前主流的LLM按照功能和应用领域进行分类整理，请参考[Model List](https://github.com/ArronAI007/Awesome-AGI/tree/main/Model-List/README.md)

## LLM Open Tool

### LLM Fine Tune

Fine Tune目录会介绍更多关于LLM微调的脚步以及开源工具或者平台的使用案例，请参考[Fine Tune](https://github.com/ArronAI007/Awesome-AGI/tree/main/Fine-Tune/README.md)

### LLM Deployment

| Description| Paper | Code | Blog |
| --- | --- | --- | --- |  
| BentoML |  | [BentoML Code](https://github.com/bentoml/BentoML) |  |  
| CLIP-API-service |  |  |  |  
| CTranslate2 |  |  |  |  
| DeepSpeed-MII |  |  |  | 
| FastLLM |  |  |  |   
| Huggingface |  |  |  |   
| JittorLLM |  |  |  |   
| LightLLM |  |  |  |  
| LMDeploy |  |  |  |  
| MLC LLM |  |  |  |  
| OneDiffusion |  |  |  |  
| OpenLLM |  |  |  |  
| Ray Serve |  |  |  |  

## LLM Prompt Engineering

## 欢迎共创

【👬🏻】欢迎Star ⭐️⭐️⭐️⭐️⭐️ && 提交 Pull requests 👏🏻👏🏻👏🏻

## 关于我

**个人主页**：wshzd.github.io

**微信公众号**：

![公众号二维码](https://i.postimg.cc/g092W4dB/ArronAI.jpg)

## 声明

以上部分资料来自网络整理，供大家学习参考，如有侵权，麻烦联系我删除！ 

WeChat：h18821656387
