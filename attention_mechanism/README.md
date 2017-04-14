# Attention Mechanism 论文选读

## 综述 paper

- [Embed, encode, attend, predict: The new deep learning formula for state-of-the-art NLP models](https://explosion.ai/blog/deep-learning-formula-nlp)

---

## 近期论文

- [Attention Correctness in Neural Image Captioning](https://arxiv.org/abs/1605.09553)
	- 2016.05
	- 对 NIC 的 attention 改进

- [Sequence to Sequence Learning as Beam-Search Optimization](https://arxiv.orCg/abs/1606.02960)
	- 2016.06
	- ?

- [Neural Machine Translation with Recurrent Attention Modeling](https://arxiv.org/abs/1607.05108)
	- 2016.07
	- 把历史的 attention activation 也考虑进去

- [Can Active Memory Replace Attention?](https://arxiv.org/abs/1610.08613)
	- 2016.10
	- 探讨了 attention mechanism 和 memory network 之间的关系

- [A Structured Self-attentive Sentence Embedding](https://arxiv.org/abs/1703.03130)
	- 2017.03
	- 把句子 embedding 成一个矩阵

---

## 早期论文

- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)
	- 2014.09, Bahdanau
	- 最早把 attention 用到机器翻译中的论文，可以把翻译的英文和法文对其(align)
	- 参考对应的没有 attention 的模型 [google seq2seq NMT](https://arxiv.org/abs/1409.3215)

- [Show, Atten and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)
	- 2015.02
	- 把 attention 用到 Image Caption 问题上

- [Deep Sentence Embedding Using LSTM Networks: Analysis and Application to Information Retrieval](https://arxiv.org/abs/1502.06922)
	- 2015.02
	- 用 LSTM 做 sentence embedding 的时候，用 attention 检测关键词

- [Describing Multimedia Content using Attention-based Encoder-Decoder Networks](https://arxiv.org/abs/1507.01053)
	- 2015.07
	- 系统总结 CNN + gated RNN + attention 在诸多课题上的应用

- [ABCNN: Attention-Based CNN for Modeling Sentence Pairs](https://arxiv.org/abs/1512.05193)
	- 2015.12
	- CNN 上的 attention
