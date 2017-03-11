## Image Caption 论文选读

### 中文的综述，博客等

- [智能单元：看图说话的AI小朋友——图像标注趣谈（上）](https://zhuanlan.zhihu.com/p/22408033)
- [智能单元：看图说话的AI小朋友——图像标注趣谈（下）](https://zhuanlan.zhihu.com/p/22520434)
- [Image Caption 任务综述 | PaperWeekly](http://mp.weixin.qq.com/s?src=3&timestamp=1489138990&ver=1&signature=xSUpxVgIS-RRb0fh0XqX0q*PNbsdKBcgbJv2mguLz0ZoSLmVqVwoVW9OPkLGQ1PWJLdPxCRiZgFCWEkoZBlD5pC**mH7Z4VpF3GvNzpLi1TK221p1Sfd3iHROtqAmwQMRxkMKDCxyotOOXnHPTqKTwc9nkIUQzyyTkzg75jqqzI=) 推荐的 paper 都相对比较新

---

### 较新的论文

- [What Value Do Explicit High Level Concepts Have in Vision to Language Problems?](https://arxiv.org/abs/1506.01144)
  - 发现用更抽象的特征会明显提高效果

- [Multimodal Pivot for Image Caption Translation， 16.01](https://arxiv.org/abs/1601.03916)
  - 多语言和 ranking 的思想做 Image Caption 

- [Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning, 2016.12](https://arxiv.org/abs/1612.01887)
  - 文本和图片都有 Attention，模型自动动态调整是从哪一个里学习

---

### 经典的论文

- [Multi-modal neural language models, 2014, Ryan Kiros](http://www.cs.toronto.edu/~rkiros/papers/mnlm2013.pdf)
  - 有些老的论文，但是又讲到怎么做检索，图片搜文本，文本搜图片

- [Unifying Visual-Semantic Embeddings with Multimodal Neural Language Models, 2014, Ryan Kiros](https://arxiv.org/abs/1411.2539)
  - 把图片和句子都嵌入到一个 multimodal vector space 中去，做余弦相似度
  - [PPT](http://www.cs.toronto.edu/~fidler/slides/2017/CSC2539/DavidMadras-CSC2539.pdf)

- [From Captions to Visual Concepts and Back, 2014.11, Microsoft Research](https://arxiv.org/abs/1411.4952)
  - 微软的论文，先识别物体，然后组成句子，最后给句子排序做检索任务。

- [Learning a Recurrent Visual Representation for Image Caption Generation](https://arxiv.org/abs/1411.5654)

- [Explain Images with Multimodal Recurrent Neural Networks, 2014.11](https://arxiv.org/abs/1410.1090)
  - 百度的论文，挺重要的模型，即 m-RNN，较早，有些设计不太好

- [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/abs/1411.4555)
  - 谷歌的文章，即 NIC 模型，tensorflow 有实现，
  - 较上面的 m-RNN 有改进，RNN 换成了 LSTM，更好的 CNN，图像的 feature 只在开始时输入了一次

- [Deep Visual-Semantic Alignments for Generating Image Descriptions, 2014.12, Andrej Karpathy, Li Fei-Fei](https://arxiv.org/abs/1412.2306)
  - 这个大家都知道了，就是注明的 NeuralTalk

- [Show, Attend and Tell: Neural Image Caption, Generation with Visual Attention, Kelvin Xu, 2015.02](https://arxiv.org/abs/1502.03044)
  - 这里把 attention 从机器翻译中运用到 Image Caption 任务
  - 代码: [arctic-captions](https://github.com/kelvinxu/arctic-captions)
