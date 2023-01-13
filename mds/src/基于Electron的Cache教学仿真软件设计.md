### 课题名称
基于Electron的Cache教学仿真软件设计

#### 论文研究方向
计算机应用

#### 题目简述
Electron是由Github开发的一个开源框架。Electron以Node.js作为运行时，以Chromium作为渲染引擎，使开发者可以使用HTML、CSS和JavaScript等前端技术栈来开发跨平台桌面GUI应用。已经有很多桌面应用采用Electron开发，其中不乏耳熟能详的知名软件，如Skype、VS CDOE、飞书等，据悉腾讯计划在2023年用Electron重构QQ。

Cache是CPU设计中的一个重要方面，是计算机组成原理中一个比较重要的知识点，也是一个难点，让学生通过仿真了解Cache运行原理，是一种有效的教学手段。

#### 本题目预期目标
1. 支持直接映像、全相联映像和组相联映像三种映像方式，包括指令cache和数据cache；
2. 用户可设置主存大小、cache大小及块（行）大小；
3. 组相联映像可设置每组块数（2块或4块）；
4. 可视化cache**物理结构**，并显示cache内容变化；
5. 能够对命中与未命中情况进行判断并表示；
6. cache性能分析功能。自动计算访问计数、命中率等参数，实时绘制参数变化曲线。
7. 编写实验指导。

#### 对学生知识与能力要求
1. 具备较好的计算机组成原理基础。
2. 熟悉Web前端开发技术。
3. 具有软件开发过程的问题分析、系统设计、程序编码、调试等基本方法和技能。

#### 主要参考资料
1. 《Electron实战 入门、进阶与性能优化》
2. 《深入浅出Electron：原理、工程与实践》
3. 《计算机组成原理》
4. Ripes开源仿真软件. https://github.com/mortbopet/Ripes
5. RARS开源仿真软件. https://github.com/TheThirdOne/rars
7. Lab 7: Caches 实验指导. https://cs61c.org/

#### 工作进度计划

2023.02.12-2023.03.05	课题调研，翻译外文资料，确定设计方案，完成开题报告	
2023.03.10-2023.04.23	设计、调试，中期检查	
2023.04.24-2023.04.30	测试，完善设计	
2023.05.01-2023.05.29	撰写毕业设计论文	
2023.05.30-2023.06.11	评审，答辩

#### 英文翻译
- Lab 7: Caches 实验指导. https://cs61c.org/fa22/labs/lab07/
  
- Ripes Cache Simulation. https://github.com/mortbopet/Ripes/blob/master/docs/cache_sim.md