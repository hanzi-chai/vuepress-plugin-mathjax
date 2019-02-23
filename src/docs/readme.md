---
home: true
title: 主页
actionText: Get Started →
actionLink: /guide/
---

## Input

<pre class="math-block">
假设 $y \geq 0$ , 而 $[\log x]$ 表示 $\log x$ 的整数部分, 设:

$$\Phi (y) = \frac {1} {2 \pi i} \int_{2 - i \infty}^{2 + i \infty} \frac {y^{\omega} \dd \omega} {\omega \left(1 + \frac {\omega} {(\log x)^{1.1}}\right)^{[ \log x ] + 1}}, x > 1$$

显见， 当 $0 \leq y \leq 1$ 时， 有 $\Phi(y) = 0$. 对于所有 $y \geq 0$, 则 $\Phi(y)$ 是一个非减函数.

当 $\log x\geq 10^4$ 及 $y\geq e^{2{(\log x)}^{-0.1}}$ 时， 则有:

$$1 - x^{- 0.1} \leq \Phi (y) \leq 1$$
</pre>

## Output

<div class="math-block">

假设 $y \geq 0$ , 而 $[\log x]$ 表示 $\log x$ 的整数部分, 设:

$$\Phi (y) = \frac {1} {2 \pi i} \int_{2 - i \infty}^{2 + i \infty} \frac {y^{\omega} \dd \omega} {\omega \left(1 + \frac {\omega} {(\log x)^{1.1}}\right)^{[ \log x ] + 1}}, x > 1$$

显见， 当 $0 \leq y \leq 1$ 时， 有 $\Phi(y) = 0$. 对于所有 $y \geq 0$, 则 $\Phi(y)$ 是一个非减函数.

当 $\log x\geq 10^4$ 及 $y\geq e^{2{(\log x)}^{-0.1}}$ 时， 则有:

$$1 - x^{- 0.1} \leq \Phi (y) \leq 1$$

</div>

<style lang="stylus">

.math-block
  font-family inherit
  padding .1rem 1.5rem
  border-left-width .5rem
  padding-right: 0rem
  border-left-style solid
  margin 1rem 0
  border-radius 0 !important
  background-color rgba(102, 128, 153, .05) !important
  border-color #D6DBDF
  color $textColor

pre.math-block
  white-space pre-wrap

</style>

::: slot footer
[MIT](https://mit-license.org/) Licensed | [VuePress](https://vuepress.vuejs.org/) Powered
:::