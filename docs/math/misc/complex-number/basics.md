# 复数

## 复数的概念

数学老师摁在墙上告诉你，二元一次方程 $ax^2 + bx + c = 0$ 在 $b^2-4ac < 0$ 时是没有根的．严格来讲，没有实数根．

一般地，方程 $x^2 = -1$ 在实数范围内无解，没有一个实数的平方是负的．

倘如直接定义 $(\sqrt{-1})^2 = -1$ 就好办了．一般地，用 $\mathrm i$ 作为虚数单位，其中 $\mathrm i = \sqrt{-1}$ 等价．

值得一提的是，虽然 $\mathrm i = \sqrt{-1}$ 等价，但为了避免混淆，除非特别声明，$\sqrt{a}$ 仍需认为 $a$ 是非负实数，并且不再使用 $\sqrt{-1}$ 这样类似的表达式．同时在印刷的时候，一般将虚数单位印刷成正体 $\mathrm i$ 而不是斜体 $i$．

实数 $a$ 和虚数单位 $\mathrm i$ 的和记作 $a + \mathrm i$，其中 $0 + \mathrm i = \mathrm i$；实数 $b$ 和虚数单位 $\mathrm i$ 的积记作 $b \mathrm i$ ，其中 $0 \times \mathrm i = 0$ ，$1 \times \mathrm i = \mathrm i$．

一般地，若 $a$ 和 $b$ 都是实数，称 $a + b \mathrm i$ 为复数，用 $z$ 表示：

$$
z = a + b \mathrm i (a, b \in \mathbb{R})
$$

其中 $a$ 称为复数 $z$ 的实部，$b$ 称为复数 $z$ 的虚部（**注意虚部是一个实数，而不是 $b\mathrm i$**）．分别记作：

$$
\Re(z) = a, \Im(z) = b
$$

所有复数的集合成为复数集，一般用 $\mathbb{C}$ 表示，其定义是：

$$
\mathbb{C} = \{ a + b\mathrm{i}\mid a, b \in \mathbb{R} \}
$$

需要记住的是，如果两个复数的实部和虚部分别相等，则认为两个复数相等；复数由其实部和虚部确定，虚部为 $0$ 认为是实数；特别的，虚部不为 $0$ 的称之为虚数，实部为 $0$ 的称之为纯虚数．

## 复数的几何意义

实数轴上每一点对应一个实数，那么是否存在一个虚数轴，上面每一点对应一个虚数呢？肯定是存在的．

在 $z = a + b \mathrm {i}, a, b \in \mathbb{R}$ 中，复数 $z$ 由实数 $a, b$ 确定，可以认为是由有序实数对 $(a, b)$ 确定的．由此，复数可以和平面直角坐标系扯上关系：

$$
z = a + b\mathrm{i} \longleftrightarrow Z(a, b)
$$

值得一提的是，此时的 $y$ 轴称虚轴， $x$ 轴称实轴，平面直角坐标系 $xOy$ 称复平面．

倘若平面内存在点 $Z(a, b)$ 连接 $OZ$ ，向量 $\overrightarrow{OZ}$ 与点 $Z(a, b)$ 有且只有一种对应方式，点 $Z(a,b)$ 也和向量 $\overrightarrow{OZ}$ 有且只有一种对应方式．这便是复数的第二种几何意义，即 $\mathbb{C}$ 中的数与点与实数轴原点形成的向量 $\overrightarrow{OZ}$ 的对应关系．

其中向量 $\overrightarrow{OZ}$ 的模也叫复数 $z = a + b \mathrm i$ 的模，记作 $\lvert z \rvert$ 或者 $\lvert a + b \mathrm{i} \rvert$ 即：

$$
\lvert z \rvert = \lvert a + b \mathrm{i} \rvert = \sqrt{a^2 + b^2 }, a, b \in \mathbb{R}
$$

值得一提的是，相等的向量表示同一个复数．

两个实部相等，虚部互为相反数的复数互为共轭复数，记作 $\overline z$．也就是说如果 $z = a + b \mathrm i$ 那么 $\overline z = a - b \mathrm i$．

## 复数的四则运算

### 加法与减法运算

复数 $z_1 = a_1 + b _ 1 \mathrm{i}$ 与 $z_2 = a_2 + b _ 2 \mathrm{i}$ 相加：

$$
z_1 + z_2 = a_1 + b_1 \mathrm{i} + a_2 + b_2 \mathrm{i} = a_1 + a_2 + (b_1 + b_2)\mathrm i
$$

复数 $z_1 = a_1 + b _ 1 \mathrm{i}$ 与 $z_2 = a_2 + b _ 2 \mathrm{i}$ 相减：

$$
z_1 - z_2 = a_1 + b_1 \mathrm{i} - a_2 + b_2 \mathrm{i} = a_1 - a_2 + (b_1 - b_2) \mathrm i 
$$

值得一提的是，向量可以使用平行四边形法则计算．

### 乘法与除法运算

复数 $z_1 = a_1 + b _ 1 \mathrm{i}$ 与 $z_2 = a_2 + b _ 2 \mathrm{i}$ 相乘：

$$
z_1 z_2 = (a_1 + b _ 1 \mathrm{i})(a_2 + b _ 2 \mathrm{i}) =
(a_1 a_2 - b_1 b_2) + (a_1 b_2 + a_2b_1)\mathrm{i}
$$

复数 $z_1 = a_1 + b _ 1 \mathrm{i}$ 与 $z_2 = a_2 + b _ 2 \mathrm{i}$ 相除：

$$
\frac{z_1}{z_2} = \frac{a_1+b_1\mathrm i}{a_2 + b_2 \mathrm i} = \frac{a_1a_2+b_1b_2}{a_2^2+b_2^2} + \frac{a_2 b_1 - a_1 b_2}{a _ 2 ^2 + b_2 ^2} \mathrm i
$$

值得一提的是，向量可以使用平行四边形法则计算．

注：$a_1, a_2, b_1, b_2 \in \mathbb{R}$，复数加法符合交换律，结合律，乘法符合分配律．
