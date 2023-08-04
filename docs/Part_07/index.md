# 实现相关主题

IMPLEMENTATION TOPICS



> “The scientist describes what is; the engineer creates what never was.”
> 				— THEODORE VON KARMAN
>
> “Always design a thing by considering it in its next larger context — a chair in a room,a room in a house,
> a house in an environment,an environment in a city plan.”
> 				— ELIEL SAARINEN



> “科学家描述了现在有的东西； 工程师创造了以前没有的东西。”
> 				— 西奥多·冯·卡门
>
> 
>
> “设计一件东西时，总是要考虑它的下一个更大的背景——房间里的椅子、房子里的房间、环境中的房子、城市规划中的环境。”
> 				— 埃利尔·萨里宁



WE HAVE THUS FAR IGNORED SEVERAL IMPORTANT TOPICS THAT BEAR ON THE usefulness and overall quality of computer arithmetic units. In some contexts—say, when we want the hardware to support two floating-point arithmetic operations per cycle on the average and do not mind that the result of each operation becomes available after many cycles—throughput might be more important than latency. Pipelining is the mechanism used to achieve high throughput while keeping the cost and size of the circuits in check. In other contexts, the size or power requirements of the arithmetic circuits are of primary concern. In some critical applications,or in harsh operating environments,tolerance to permanent and transient hardware faults might be required. Finally, ease of implementation with flexible hardware components,such as fieldprogrammable gate arrays, rests upon certain special provisions in the design. Our discussions in this part should be viewed as windows into advanced implementation techniques. Each of the following four chapters could be expanded into a book.

到目前为止，我们忽略了与计算机算术单元的实用性和整体质量有关的几个重要主题。 在某些情况下，例如，当我们希望硬件平均每个周期支持两个浮点算术运算，并且不介意每个运算的结果在多个周期后才可用时，吞吐量可能比延迟更重要。 流水线是一种用于实现高吞吐量同时控制电路成本和尺寸的机制。 在其他情况下，运算电路的尺寸或功率要求是首要考虑的问题。 在某些关键应用程序或恶劣的操作环境中，可能需要容忍永久性和暂时性硬件故障。 最后，灵活的硬件组件（例如现场可编程门阵列）的易于实现取决于设计中的某些特殊规定。 我们在这一部分的讨论应被视为了解高级实现技术的窗口。 以下四章每一章都可以扩充成一本书。



-   [第二十五章 高吞吐量算术](25.md) High-Throughput Arithmetic
-   [第二十六章 低功耗算术](26.md) Low Power Arithmetic
-   [第二十七章 容错算术](27.md) Fault-Tolerant Arithmetic
-   [第二十八章 可重构算术](28.md) Reconfigurable Arithmetic