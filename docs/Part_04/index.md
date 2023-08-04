# 除法

DIVISION



> “Probably nothing in the modern world could have more astonished a Greek mathematician than to learn that . . . a large proportion of the population of Western Europe could perform the operation of division for the largest numbers.”
> 				— ALFRED WHITEHEAD , AN INTRODUCTION TO MATHEMATICS , 1911

> “To divide one’s life by years is of course to tumble into a trap set by our own arithmetic.”
> 				— CLIFTON FADIMAN



> “在现代世界中，也许没有什么比得知这一点更让希腊数学家感到惊讶的了…… 西欧的很大一部分人口可以进行最大数的除法运算。”
> 			— 阿尔弗雷德·怀特海德，《数学导论》，1911

> “用岁月来划分一个人的生命，当然会陷入我们自己算术设置的陷阱。”
> 			— 克利夫顿·法迪曼



DIVISION IS THE MOST COMPLEX OF THE FOUR BASIC ARITHMETIC OPERATIONS and the hardest one to speed up. Thus, dividers are more expensive and/or slower than multipliers. Fortunately, division operations are also less common than multiplications.Two classes of dividers are discussed here. In digit-recurrence schemes, the quotient is generated one digit at a time, beginning at the mostsignificant end. Binary versions of digit-recurrence division can be implemented through shifting and addition, in much the same way as shift/add multiplication schemes. Determining the digits of the quotient from the most-significant end allows us to“converge” to a k-digit quotient in k cycles. Speeding up of division via reducing the number of shift/add cycles leads to high-radix dividers. Array dividers as well as convergence methods that require far fewer than k iterations, with each iteration being more complex, are also discussed. This part is composed of the following four chapters:

**除法是四种基本算术运算中最复杂的运算**，也是最难加速的运算。 因此，除法器比乘法器更昂贵和/或更慢。 幸运的是，除法运算也不如乘法常见。这里讨论两类除法器。 在数字循环方案中，商从最高有效端开始一次生成一位数字。 二进制版本的数字循环除法可以通过移位和加法来实现，其方式与移位/加法乘法方案非常相似。从最高有效端确定商的数字使我们能够用 k 周期“收敛”为 k 位数字的商。 通过减少移位/加法周期的数量来加速除法，就是高基数除法器。 还讨论了数组除法器以及需要远少于 k 次迭代的收敛方法，并且每次迭代都更加复杂。 本部分由以下四章组成：



-   [第十三章 基础除法方案](13.md) Basic Division Schemes
-   [第十四章 高基除法器](14.md) High-Radix Dividers
-   [第十五章 其它除法器](15.md) Variations in Dividers
-   [第十六章 除法的收敛算法](16.md) Division by Convergence