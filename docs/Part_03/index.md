# 乘法

MULTIPLICATION



> “At least one good reason for studying multiplication and division is that there is an infinite number of ways of performing these operations and hence there is an infinite number of PhDs (or expenses-paid visits to conferences in the USA) to be won from inventing new forms of multiplier.”
> 				— ALAN CLEMENTS , THE PRINCIPLES OF COMPUTER  HARDWARE , 1986

> “Civilization is a limitless multiplication of unnecessary necessaries.”
> 				— MARK TWAIN



> *“研究乘法和除法的至少一个充分理由是，执行这些运算的方法有无数种，因此可以通过发明新形式的乘法赢得无数的博士学位（或免费访问美国的会议）的机会。 ”*
> 				— 艾伦·克莱门茨，《计算机硬件原理》，1986 年

> *“文明是不必要的必需品的无限增殖。”*
> 				— 马克·吐温



MULTIPLICATION, OFTEN REALIZED BY k CYCLES OF SHIFTING AND ADDING , IS a heavily used arithmetic operation that figures prominently in signal processing and scientific applications. In this part, after examining shift/add multiplication schemes and their various implementations, we note that there are but two ways to speed up the underlying multioperand addition: reducing the number of operands to be added leads to high-radix multipliers, and devising hardware multioperand adders that minimize the latency and/or maximize the throughput leads to tree and array multipliers. Of course, speed is not the only criterion of interest. Cost, chip area, and pin limitations favor bit-serial designs, while the desire to use available building blocks leads to designs based on additive multiply modules. Finally, the special case of squaring is of interest as it leads to considerable simplification. This part consists of the following four chapters:

**乘法通常通过 k 个移位和加法循环来实现，是**一种广泛使用的算术运算，在信号处理和科学应用中占有重要地位。 在这一部分中，在检查了移位/加法乘法方案及其各种实现之后，我们注意到只有两种方法可以加速底层多操作数加法：减少要添加的操作数数量导致高基数乘法器，以及设计最小化延迟和/或最大化吞吐量的硬件多操作数加法器导致树和数组乘法器。 当然，速度并不是兴趣的唯一标准。 成本、芯片面积和引脚限制有利于位串行设计，而使用可用构建块的愿望导致基于加法乘法模块的设计。 最后，平方的特殊情况很有趣，因为它可以带来相当大的简化。 本部分由以下四章组成：



-   [第九章 基础的乘法方案](09.md) Basic Mutiplication Schemes
-   [第十章 高基乘法器](10.md) High-Radix Mutipliers
-   [第十一章 树型乘法器与阵列乘法器](11.md) Tree and Array Multipliers
-   [第十二章 其它乘法器](12.md) Variations in Multipliers