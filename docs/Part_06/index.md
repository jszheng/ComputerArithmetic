# 特殊函数求值 

FUNCTION EVALUATION



> “I wrote this book and compiled in it everything that is necessary for the computer, avoiding both boring verbosity and misleading brevity.”
> 				— GHIYATH AL-DIN JAMSHID AL-KASHI, THE KEY TO COMPUTING (MIFTAH AL-HISABI ) , 1427
>
> “Someone told me that each equation I included in the book would halve the sales.”
> 				— STEPHEN HAWKING , A BRIEF HISTORY OF TIME , 1988



> “我写了这本书，并在其中汇编了计算机所需的所有内容，避免了无聊的冗长和误导性的简洁。”
> 				— GHIYATH AL-DIN JAMSHID AL-KASHI，计算的关键 (MIFTAH AL-HISABI)，1427
>
> “有人告诉我，我在书中包含的每个方程式都会使销售额减半。”
> 				— 史蒂芬·霍金，《时间简史》，1988



ONE WAY OF COMPUTING FUNCTIONS SUCH AS  √x, SIN x, TANH x, LN x, AND $e^x$ IS to evaluate their series expansions by means of addition, multiplication, and division operations. Another is through convergence computations of the type used for evaluating the  functions z/d and 1/d in Chapter 16. In this part, we introduce several methods for evaluating elementary and other functions.We begin by examining the important operation of extracting the square root of a number, covering both digit-recurrence and convergence square-rooting methods. We then devote two chapters to coordinate rotation digital computer (CORDIC) algorithms, other convergence methods, approximations, and merged arithmetic. We conclude by discussing versatile, and highly flexible, tablelookup schemes,which are assuming increasingly important roles as advances in digital technology lead to ever cheaper and denser memories.This part is composed of the following four chapters:



计算 √x、SIN x、TANH x、LN x 和 $e^x$ 等函数的一种方法是通过加法、乘法和除法运算来计算它们的级数展开式。 另一种方法是通过第 16 章中用于求函数 $z/d$ 和 $1/d$ 的类型的收敛计算。在这一部分中，我们介绍几种评估初等函数和其他函数的方法。我们首先检查提取平方的重要操作 数字的根，涵盖数字递归和收敛平方根方法。 然后，我们用两章来介绍坐标旋转数字计算机（CORDIC）算法、其他收敛方法、近似和合并算法。 最后，我们讨论了通用且高度灵活的查表方案，随着数字技术的进步导致存储器变得更加便宜和密集，这些方案正在发挥越来越重要的作用。这部分由以下四章组成：



-   [第二十一章 平方根算法](21.md) Square Rooting Methods
-   [第二十二章 CORDIC算法](22.md) The CORDIC Algorithms
-   [第二十三章 其它函数求值方法](23.md) Variations in Function Evaluation
-   [第二十四章 查表法算术](24.md) Arithmetic by Table Lookup