# 第二版序言

自《COMPUTER ARITHMETIC : Algorithms and Hardware Designs》第一版出版以来，已经过去了十年。尽管过去十年算术算法和实现技术在不断地进步，但该书的顶层设计仍然很合理。因此除了包括一个有关可重构算术的新章节外，图P.1中描述的部分（Part）和章节将在第二版保持不变。新的一章取代了原先的第28章，其原先内容被安排到了附页中。作者层考虑添加一个附录，以列出网站和其它互联网资源，以供进一步学习。但互联网资源的位置和内容是高度动态的，因此作者决定将这些信息放在作者为本书建立的配套网站上，可通过他的个人网站访问：

http://www.ece.ucsb.edu/~parhami/

之所以添加有关可重构算术的新章节，是因为现在越来越多的算术功能是在FPGA或类FPGA的可配置逻辑器件上实现的。这类方法对于新设计的原型开发、小批量或独一无二的系统，或者需要在现场升级更新，快速发展的产品，都是非常具有吸引力的。因此描述在这种情况下被认为合理的设计以及设计策略也是非常有用的。新材料与第七部分的其它三章能很好地融合在一起，所有的这些都是有关实现（implement）的主题。新的第28章涉及的例子包括基于查找表的函数求值，以及FPGA上的几个加法器和乘法器设计。

第二版也进行了一些扩充、改进、澄清和更正。许多节都新增了材料，以反映新的想法与发展。在许多情况下，旧的小结被合并，并为新的想法或设计创建了新的小节。在第二版中，新的合扩充的主题以章节位长度进行了处理，包括以下内容（括号内为章节编号）：

-   模二操作数和多操作数加法器（7.6, 8.6）
-   截断树和阵列乘法器（11.4）
-   重叠商位选择（15.2）
-   蒙哥马利模乘法/约化（15.4）
-   作为除法特殊情况的倒数（15.5）
-   浮点FMA单元（fused-multiply-add）（18.5）
-   区间算数，包括区间牛顿迭代法（20.6）
-   bipartite table和multipartie table方法（24.6）

此外还引入了新的章末问题，使得问题的总数达到了718个。作者没在这篇序言中加入新的一般参考资料，而是貌美地更新和拓展了第一版序言末尾的参考资料清单，以便提供一个单一的综合清单。

一如既往，作者欢迎大家就发现的错误、需进一步澄清的主题、问题的解决方案以及关于新主题或练习的想法进行交流



Behrooz Parhami

August 2009, Santa Barbara, CA