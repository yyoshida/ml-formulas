# Gauss集中不等式 （Gaussian Concentration inequality）

## ステートメント
$X_1, \ldots, X_N$を独立同分布で，各$X_i$は標準正規分布に従うとする．
$f: \mathbb{R}^N \to \mathbb{R}$を$L$リプシッツ関数とし，$Z=f(X)$とする．
この時任意の$t>0$に対し，

$$
\mathbb{P}\\{Z -\mathbb{E}Z \geq t \\} \leq e^{-\frac{t^2}{2L^2}}
$$
が成立する．

## 証明の概要

* いくつかの証明方法があるが，1つの方法として，対数ソボレフ不等式から，$Z$の生成母関数の対数を二次関数で抑えられ，その係数がリプシッツ定数の逆数に比例することを示せる．
この一連の証明の流れをHerbstの議論（Herbst's argument）という．
* ガウス過程に関する不等式Tsirelson-Ibragimov-Sudakov（TIS）の定理の特別な場合とみなせる．

## 出典
Boucheron et al. Concentration inequalities: A Nonasymptotic Theory of Independence (2013)
Evarist Giné and Richard Nickl, Mathematical Foundations of Infinite-Dimensional Statistical Models (2015)