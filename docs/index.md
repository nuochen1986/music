## liunuochen's music blog
### 个人小站
- 这是我的个人博客小站，里面会存放一些关于音乐的资料，还有自己手打的谱子等，这些资料仅供参考学习使用。
- 我本人比较喜欢音乐，可惜小时候没有机会学这些。现在业余陪儿子练琴之外，会学习一些音乐知识，这个小站就是为了记录自己了解到的关于音乐的点滴。
- 由于是自学，有些知识或见解不一定正确，欢迎指正。
### 代码高亮
- 代码高亮示例
```
\version "2.20.0"
\include "english.ly"

\score {
  \new Staff {
    \key d \major
    \numericTimeSignature
    \time 2/4
    <cs' d'' b''>16 <cs' d'' b''>8.
    %% Here: the tie on the D's looks funny
    %% Too tall? Left-hand endpoint is not aligned with the B tie?
    ~
    <cs' d'' b''>8 [ <b d'' a''> ]
  }
}
```
### 公式支持
$$
\displaystyle\tag{1}
\nabla\times\vec{E}=-\frac{\partial\vec{B}}{\partial t}
$$
$$
\displaystyle\tag{2}
\nabla\times\vec{B}=\vec{J}+\frac{\partial\vec{D}}{\partial t}
$$
$$
\displaystyle\tag{3}
\nabla\cdot\vec{E}=\rho
$$
$$
\displaystyle\tag{4}
\nabla\times\vec{B}=0
$$
### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
