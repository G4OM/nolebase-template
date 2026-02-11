## 1. 概率密度函数（PDF）

### 标准形式

对于均值为 $\mu$，方差为 $\sigma^2$ 的正态分布：

$$
f(x \mid \mu, \sigma^2) = \frac{1}{\sqrt{2\pi\sigma^2}} \exp\left(-\frac{(x-\mu)^2}{2\sigma^2}\right)
$$

### 标准正态分布 ($\mu=0, \sigma=1$)

$$
\phi(x) = \frac{1}{\sqrt{2\pi}} e^{-x^2/2}
$$

### 参数说明

- $\mu$：均值（位置参数）
- $\sigma$：标准差（尺度参数）
- $\sigma^2$：方差

1805-年[勒让德](https://zh.wikipedia.org/wiki/%E9%98%BF%E5%BE%B7%E9%87%8C%E5%AE%89-%E9%A9%AC%E9%87%8C%C2%B7%E5%8B%92%E8%AE%A9%E5%BE%B7)首创最小二乘法计算彗星轨道
1809-[高斯](https://zh.wikipedia.org/wiki/%E5%8D%A1%E7%88%BE%C2%B7%E5%BC%97%E9%87%8C%E5%BE%B7%E9%87%8C%E5%B8%8C%C2%B7%E9%AB%98%E6%96%AF)发现误差分布服从的规律——正态分布。并且拿最小二乘法验证。


