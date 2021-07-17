# articles
这里汇集我所写的网络文章，均遵循 CC BY-NC-SA 4.0 开源共享协议。

大部分为学习时的记录，基本都是文章，不包含项目。

*TODO：等到 小站 部署在 gitee 之后，再添加 小站的链接。*

------

## 【规范】系列

集大成者，愿与君共寻人世间意义。该系列 真-永远更新（有生之年）。

### 【目录贴】软硬件规范化

软硬件规范化的意义、内容、实践方面的介绍，还有远景/展望未来方面的内容。

[Github](https://github.com/Staok/norm-of-software-and-hardware/blob/main/%E5%85%B3%E4%BA%8E%E8%BD%AF%E7%A1%AC%E4%BB%B6%E8%A7%84%E8%8C%83%E5%8C%96%E7%9A%84%E8%AF%B4%E6%98%8E.md)；[知乎](https://zhuanlan.zhihu.com/p/360100358)；小站。

### C & MCU 编写规范

"低耦合，可重用，参数化，注释全"，个人总结的抽象层面非常实用部分的集大成者。

[Github](https://github.com/Staok/coding-style-and-more/blob/main/C%20%26%20MCU%E7%BC%96%E5%86%99%E8%A7%84%E8%8C%83%E5%92%8C%E5%85%B6%E4%BB%96.md)；[知乎](https://zhuanlan.zhihu.com/p/350839857)；小站。

### SCH & PCB 设计规范和 AD 的使用

个人总结的抽象层面非常实用部分的集大成者。

[Github](https://github.com/Staok/thoughs-about-hardware-design/blob/master/SCH%20%26%20PCB%20%E8%AE%BE%E8%AE%A1%E8%A7%84%E8%8C%83%E5%92%8C%20AD%20%E7%9A%84%E4%BD%BF%E7%94%A8.md)；[知乎](https://zhuanlan.zhihu.com/p/356679916)；小站。

### HDL & FPGA 学习和规范

初步学习的一些记录。

[知乎](https://zhuanlan.zhihu.com/p/356856108)；小站。

## 【主线剧情】系列

吾将上下而求索。主要围绕嵌入式 ARM SoC 以及 Linux 的学习记录。

### 【主线剧情01】ARM & i.MX6ULL 基础学习记录

ARM 寄存器、汇编、GCC、Makefile 及其模板、imx6ull 的启动流程、异常与 GIC、ARM SoC 启动文件示例。

[Github](https://github.com/Staok/ARM-Linux-Study/blob/main/ARM%20%26%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95/%E3%80%90%E4%B8%BB%E7%BA%BF%E5%89%A7%E6%83%8501%E3%80%91ARM%20IMX6ULL%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95.md)；[知乎](https://zhuanlan.zhihu.com/p/362115513)；小站。

### 【主线剧情02】ARM & Linux 基础学习记录

Linux 文件系统、Linux 基本 Shell 命令、Vim 使用、ubuntu 包管理、换源和系统变量管理、Linux 驱动、应用编译和构建系统体验、PC 与嵌入式板传输文件方式汇总。

[Github](https://github.com/Staok/ARM-Linux-Study/blob/main/ARM%20%26%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95/%E3%80%90%E4%B8%BB%E7%BA%BF%E5%89%A7%E6%83%8502%E3%80%91ARM%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95.md)；[知乎](https://zhuanlan.zhihu.com/p/363051138)；小站。

### 【主线剧情 番外01】ARM & SOC 系列快速鸟瞰

现今主流处理器架构和内核层，ARM架构处理器的架构层、内核层和具体芯片（举例），ARM Cortex-A 系列对比、Linux 系统方案的优势介绍。

[Github](https://github.com/Staok/ARM-Linux-Study/blob/main/ARM%20%26%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95/%E3%80%90%E4%B8%BB%E7%BA%BF%E5%89%A7%E6%83%85%20%E7%95%AA%E5%A4%9601%E3%80%91ARM%20%E7%B3%BB%E5%88%97%E5%BF%AB%E9%80%9F%E9%B8%9F%E7%9E%B0.md)；[知乎](https://zhuanlan.zhihu.com/p/369245951)；小站。

### 【主线剧情 03】Uboot 移植基础详解

在非常新的 uboot 版本（2019 以及之后）上面的 i.mx8mm 移植超细步骤，还包括嵌入式领域的 boot 的思想介绍、u-boot 的启动流程细解、mkimage 工具细解、u-boot 常用命令等。

[Github](https://github.com/Staok/ARM-Linux-Study/blob/main/ARM%20%26%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95/%E3%80%90%E4%B8%BB%E7%BA%BF%E5%89%A7%E6%83%8503%E3%80%91NXP%20i.MX%20%E7%B3%BB%E5%88%97%20u-boot%20%E7%A7%BB%E6%A4%8D%E5%9F%BA%E7%A1%80%E8%AF%A6%E8%A7%A3.md)；[知乎](https://zhuanlan.zhihu.com/p/373505974)；小站。

### 【主线剧情 番外02】设备树详解

设备树基本概念、基本语法、常用节点、标准属性等。关于 Linux 中设备树操作函数 以及 用设备树建立和控制设备 在后面的 Linux 应用编程 文章详解。

[Github](https://github.com/Staok/ARM-Linux-Study/blob/main/ARM%20%26%20Linux%20%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95/%E3%80%90%E4%B8%BB%E7%BA%BF%E5%89%A7%E6%83%85%20%E7%95%AA%E5%A4%9602%E3%80%91%E8%AE%BE%E5%A4%87%E6%A0%91%E8%AF%A6%E8%A7%A3.md)；[知乎](https://zhuanlan.zhihu.com/p/376755248)；小站。

## 【读标准】系列

读 IEEE 1451 智能传感器接口标准源文及其周边论文、文章、PPT 等的总结性记录。确定路线后就剩体力劳动，所以画饼人在快乐星球。

### 【读标准01】IEEE 1541 智能传感器接口标准介绍

名词/概念释义、标准簇/标准模型、1451.0 标准的 NCAP 与 TIM 的通讯（包括 消息 和 TEDS）、TIM/传感器 的状态图、1451 标准的局限性。

[Github](https://github.com/Staok/IEEE-1451-study/blob/main/%E8%AF%BB%E6%A0%87%E5%87%8601-IEEE1541-%E6%99%BA%E8%83%BD%E4%BC%A0%E6%84%9F%E5%99%A8%E6%8E%A5%E5%8F%A3%E6%A0%87%E5%87%86%E4%BB%8B%E7%BB%8D/%E8%AF%BB%E6%A0%87%E5%87%8601-IEEE1541-%E6%99%BA%E8%83%BD%E4%BC%A0%E6%84%9F%E5%99%A8%E6%8E%A5%E5%8F%A3%E6%A0%87%E5%87%86%E4%BB%8B%E7%BB%8D.md)；[知乎](https://zhuanlan.zhihu.com/p/390401130)；小站。

### 【读标准02】IEEE1541.5 智能无线传感器标准介绍

对 1451.5 中与 1451.0 不同部分的介绍，有 命令集、PHY TEDS、WLAN 等。

[Github](https://github.com/Staok/IEEE-1451-study/blob/main/%E8%AF%BB%E6%A0%87%E5%87%8602-IEEE1541.5-%E6%99%BA%E8%83%BD%E6%97%A0%E7%BA%BF%E4%BC%A0%E6%84%9F%E5%99%A8%E6%A0%87%E5%87%86%E4%BB%8B%E7%BB%8D/%E8%AF%BB%E6%A0%87%E5%87%8602-IEEE1541.5-%E6%99%BA%E8%83%BD%E6%97%A0%E7%BA%BF%E4%BC%A0%E6%84%9F%E5%99%A8%E6%A0%87%E5%87%86%E4%BB%8B%E7%BB%8D.md)；知乎；小站。

## 【技术杂文】



### PCIe接口及其衍生接口大总结

[知乎](https://zhuanlan.zhihu.com/p/388272103)，小站。

### 罗列各种开源代码的公共协议以供选择

[Github](https://github.com/Staok/Public-License-List)，小站。

### FQ

[Github](https://github.com/Staok/FQ/blob/master/FQ%E6%AD%A3%E5%BC%8F%E6%B5%81%E7%A8%8B.md)，小站。

### 【简明自控】为什么特征方程如此重要

[知乎](https://zhuanlan.zhihu.com/p/115199985)。

## 【日常杂文】

### 科幻小说《请留在未来》

[Github](https://github.com/Staok/Please-stay-in-the-future)；[知乎](https://zhuanlan.zhihu.com/p/361265924)；小站；[Bilibili](https://www.bilibili.com/read/cv6305018)。

### 科幻小说《请留在未来》-注解篇

[Github](https://github.com/Staok/Please-stay-in-the-future)；[知乎](https://zhuanlan.zhihu.com/p/148983427)；小站；[Bilibili](https://www.bilibili.com/read/cv6451813)。

### 【杂谈】只剩结论的故事便是短句合集（长期更新）

[知乎](https://zhuanlan.zhihu.com/p/196406624)，小站。

### 【杂谈】师之传达（长期更新）

[知乎](https://zhuanlan.zhihu.com/p/363129321)，小站。

### 【考研】噫嘘唏，考研个人经验汇总

[知乎](https://zhuanlan.zhihu.com/p/235480366)；小站。
