## Image Caption 论文选读

### 中文的综述，博客等

- [智能单元：看图说话的AI小朋友——图像标注趣谈（上）](https://zhuanlan.zhihu.com/p/22408033)
- [智能单元：看图说话的AI小朋友——图像标注趣谈（下）](https://zhuanlan.zhihu.com/p/22520434)
  - 讲了很多 Image Caption 基础的知识，必读
- [Image Caption 任务综述 | PaperWeekly 第二十二期](http://weixin.sogou.com/weixin?type=2&query=Paper+Weekly+Image+Caption)
  - 推荐的 paper 都相对比较新

---

### 较新的论文

- [Multimodal Convolutional Neural Networks for Matching Image and Sentence](https://arxiv.org/abs/1504.06063)
  - 2015.04, m-CNN，华为诺亚方舟实验室的论文
  - 不多的 CNN 架构，很有参考价值

- [What Value Do Explicit High Level Concepts Have in Vision to Language Problems?](https://arxiv.org/abs/1506.01144)
  - 2015.06
  - 发现用更抽象的特征会明显提高效果

- [Multimodal Pivot for Image Caption Translation](https://arxiv.org/abs/1601.03916)
  - 2016.01
  - 多语言和 ranking 的思想做 Image Caption 

- [Instance-aware Image and Sentence Matching with Selective Multimodal LSTM](https://arxiv.org/abs/1611.05588)
  - 2016.11
  - 即 sm-LSTM 模型，用了复杂的 attention model，新文章的参考文献应该会很有价值

- [Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning](https://arxiv.org/abs/1612.01887)
  - 2016.12
  - 文本和图片都有 Attention，模型自动动态调整是从哪一个里学习

---

### 经典的论文

- [Multi-modal neural language models](http://www.cs.toronto.edu/~rkiros/papers/mnlm2013.pdf)
  - 2014, Ryan Kiros
  - 有些老的论文，但是又讲到怎么做检索，图片搜文本，文本搜图片

- [Unifying Visual-Semantic Embeddings with Multimodal Neural Language Models](https://arxiv.org/abs/1411.2539)
  - 2014, Ryan Kiros
  - 把图片和句子都嵌入到一个 multimodal vector space 中去，做余弦相似度
  - [PPT](http://www.cs.toronto.edu/~fidler/slides/2017/CSC2539/DavidMadras-CSC2539.pdf)

- [From Captions to Visual Concepts and Back](https://arxiv.org/abs/1411.4952)
  - 2014.11, Microsoft Research
  - 微软的论文，先识别物体，然后组成句子，最后给句子排序做检索任务。

- [Learning a Recurrent Visual Representation for Image Caption Generation](https://arxiv.org/abs/1411.5654)
  - 2014.11

- [Explain Images with Multimodal Recurrent Neural Networks, 2014.11](https://arxiv.org/abs/1410.1090)
  - 2014.11 m-RNN, Baidu Research
  - 百度的论文，挺重要的模型，即 m-RNN，较早，有些设计不太好

- [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/abs/1411.4555)
  - 2014.11, Google NIC
  - 较上面的 m-RNN 有改进，RNN 换成了 LSTM，更好的 CNN，图像的 feature 只在开始时输入了一次

- [Deep Fragment Embeddings for Bidirectional Image Sentence Mapping](https://arxiv.org/abs/1406.5679)
  - 2014.06, Andrej Karpathy 和 Li Fei-Fei 的论文

- [Deep Visual-Semantic Alignments for Generating Image Descriptions](https://arxiv.org/abs/1412.2306)
  - 2014.12
  - Andrej Karpathy, Li Fei-Fei, 这个大家都知道了，就是著名的 NeuralTalk

- [Show, Attend and Tell: Neural Image Caption, Generation with Visual Attention](https://arxiv.org/abs/1502.03044)
  - 2015.02, Kelvin Xu
  - 这里把 attention 从机器翻译中运用到 Image Caption 任务
  - 代码: [arctic-captions](https://github.com/kelvinxu/arctic-captions)
