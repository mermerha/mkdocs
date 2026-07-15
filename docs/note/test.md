# code and math
## 寻找mkdocs能否识别代码和数学公式
### 这是在接入obsidian之后的一次运用


### 首先来看code
=== "C"
``` c
#include<stdio.h>
int main{
return 0;
}
```

=== "python"
#### 再来看数学公式块的编写

$e^x =1+x+\frac{x^2}{2}+\frac{x^3}{3!}+\cdots$


$$
\begin{aligned}
e^{i\pi} =-1 \\
E = mc^2
\end{aligned}
$$
#### note部分
!!! note
    这是一个mnote

!!! abstract
    这是一个概要

!!! danger
    这是一个警告

!!! warning
	这个是一个真正的警告

??? note "笔记"
    折叠的标题

???+ note "展开笔记"
    这是一个展开的笔记


=== "标号一"

    这是第一块内容
    有很多可以看的东西

=== "标号二"

    这是第二块内容

=== "标号三"

    第三部分

=== "标号四"

    第四部分


??? note "可以折叠"
    折叠的部分


