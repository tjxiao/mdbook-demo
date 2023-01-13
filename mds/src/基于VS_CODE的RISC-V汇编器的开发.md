### 课题名称
基于VS CODE的RISC-V汇编器的开发

#### 论文研究方向
计算机应用

#### 题目简述
Visual Studio Code（简称VSCode）是Microsoft开发的代码编辑器，它支持Windows，Linux和macOS等操作系统以及开源代码。它支持测试，并具有内置的Git版本控制功能以及开发环境功能，例如代码完成，代码段和代码重构等。

RISC-V是一个基于精简指令集（RISC）原则的开源指令集架构（ISA）。与大多数指令集相比，RISC-V指令集可以自由地用于任何目的，允许任何人设计、制造和销售RISC-V芯片和软件。该指令集具有众多支持的软件，这解决了新指令集通常的弱点。

江苏大学远程FPGA虚拟实验平台为用户提供了在线FPGA实验环境。目前支持学生完成逻辑电路实验与CPU实验，但是在进行CPU实验时，需要借助第三方软件Ripes进行RISC-V的汇编工作，但是Ripes产生的格式与远程实验平台不兼容。

#### 本题目预期目标
1. 以VS CODE插件的形式实现RISC-V RV32I指令集的汇编器。
2. 支持基本的伪指令。
3. 支持语句标号，分支转移指令的目的地址可用语句标号表示。
4. 常量支持十六进制和十进制表示。
5. 能够以反汇编的形式显示汇编结果的程序清单。
6. 能够以Welab远程实验平台的json格式显示汇编结果并导出。

#### 对学生知识与能力要求
1. 具备一定的程序设计、编写和调试的能力；同时具备较强的自学和钻研能力。
2. 具备较好的“计算机组成原理”理论和实践基础。
3. 对RISC-V指令集有一定的了解。

#### 主要参考资料
1. 《Visual Studio Code 权威指南》
2. 《RISC-V-Reader-Chinese-v2p1》
3. 《计算机组成原理》

#### 英文翻译
- RISC-V Assembly Programmer's Manual. https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md

- RISC-V Venus Simulator. https://marketplace.visualstudio.com/items?itemName=hm.riscv-venus

- Venus Reference. https://cs61c.org/fa22/resources/venus-reference/

#### 工作进度计划

2023.02.12-2023.03.05	课题调研，翻译外文资料，确定设计方案，完成开题报告	
2023.03.10-2023.04.23	设计、调试，中期检查	
2023.04.24-2023.04.30	测试，完善设计	
2023.05.01-2023.05.29	撰写毕业设计论文	
2023.05.30-2023.06.11	评审，答辩
