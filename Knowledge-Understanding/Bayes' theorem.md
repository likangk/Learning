# 贝叶斯公式的理解
$$
P(H|E)=\frac{P(H)P(E|H)}{P(E)}
        =\frac{P(H)P(E|H)}{P(H)P(E|H)+P(\lnot{H})P(E|\lnot{H}))}
$$

* E：证据, evidence
* H：假设, hypothesis
* P：概率, probability

- 先验概率：$P(H)$，整个概率空间中，假设成立的概率
- 似然概率：$P(E|H)$，证据对概率空间的限制比例，针对具体假设空间
- $P(H)P(E|H)$：既假设成立也证据成立的空间
- 后验概率：$P(H|E)$，证据成立的空间中，假设成立的概率


贝叶斯公式是求在拥有先验情况下，证据下假设的概率$P(H|E)$。即已知证据的情况下，对假设成立的量化看法。

1. 已知证据的情况下，概率空间被限制为$P(E)$。
2. 证据对$H$和 $\lnot{H}$的限制不同。如果限制相同，即似然概率相同$P(E|H)=P(E|\lnot{H})$，则为无关的证据，先验不会改变后验概率。
3. 贝叶斯公式说明了证据对不同的假设空间限制的比例。也说明了假设和证据这两个变量依赖程度。


### 心理学
* 不考虑先验是非理性的（心理学实验，Kahneman、Tversky)。
* 数字、面积比抽象的公式更容易理解。proportions(比例) -> probability(概率) -> uncertainty(不确定性)
* 证据不应直接决定看法(后验)，而是更新看法。对于后验的判断错误，主要是先验给的太抽象。

### 简单证明
$$
P(A|B)P(B)=P(AB)=P(B|A)P(A)
$$

在给定假设求证据更容易写出时，可以两者交换，贝叶斯公式可以变换

---
## 学习视频
3Blue1Brown

https://www.bilibili.com/video/BV1R7411a76r