# 实数算数

REAL ARITHMETIC 



> “It is the mark of an educated man to look for precision in each class of things just so far as the nature of the subject admits.”
> 				— ARISTOTLE
>
> “All exact science is dominated by the idea of approximation.”
> 				— BERTRANDA . RUSSELL



> “受过教育的人的标志是在每一类事物的本质允许的范围内寻求精确性。”
> 				— 亚里士多德
> “所有精确科学都受近似思想的支配。”
> 				— 贝特兰达.罗素



IN MANY SCIENTIFIC AND ENGINEERING COMPUTATIONS, NUMBERS IN A WIDE RANGE, from very small to extremely large, are processed. Fixed-point number representations and arithmetic are ill-suited to such applications. For example, a fixed-point decimal number system capable of representing both $10^{−20}$ and $10^{20}$ would require at least 40 decimal digits and even then, would not offer much precision with numbers close to $10^{−20}$.Thus,we need special number representations that possess both a wide range and acceptable precision. Floating-point numbers constitute the primary mode of real arithmetic in most digital systems. In this part, we discuss key topics in floating-point number representation, arithmetic, and computational errors.Additionally,we cover alternative representations,such as logarithmic and rational number systems,that can offer certain advantages in range and/or accuracy. This part is composed of the following four chapters:

**在许多科学和工程计算中，都会处理从非常小到极大的各种数字**。 定点数表示和算术不适合此类应用。 例如，能够表示 $10^{−20}$ 和 $10^{20}$ 的定点十进制数字系统将需要至少 40 位十进制数字，即使如此，也无法为接近 $10^{−20}$ 的数字提供太多精度。因此，我们需要特殊的数字表示形式可以同时表达很大的范围和可接受的精度。浮点数构成了大多数数字系统中实际算术的主要模式。 在这一部分中，我们讨论浮点数表示、算术和计算误差方面的关键主题。此外，我们还介绍了其他变种表示，例如对数和有理数系统，它们可以在范围和/或精度方面提供一定的优势。 本部分由以下四章组成：



-   [第十七章 浮点数表示](17.md) Floating-Point Representations
-   [第十八章 浮点数运算](18.md) Floating-Point Operations
-   [第十九章 误差与误差控制](19.md) Errors and Error Control
-   [第二十章 精确可靠的算术](20.md) Precise and Certifiable Arithmetic