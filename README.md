# OWL Ontology (本体) Pizza.owl (中文版) 学习与建模实践

这是pizza.owl的本体模型教程的中文版本与建模实践的源码仓库，Pizza Tutorial是一个非常著名的用来学习本体(Ontology)理论并练习使用Protégé(本体编辑器)的教程。

你可以在这里找到作者Michael DeBellis针对新版pizza.owl教程的推文：[New Protégé Pizza Tutorial](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial)

本人在2023年拜读这个教程的过程中，录制了各个建模步骤的系列视频并首先在YouTube上进行了分享，两年来累计获得了超过五万次的观看，并收到了许多观众朋友们的问题，故也陆续将视频在其他平台上发布分享，如下：

- [YouTube: Ontology Practice - Build pizza.owl in Protégé](https://www.youtube.com/playlist?list=PL6DEHvciXKeUx4P32B3hKMK1t6mC8RhsW)
- [抖音： 使用Protege建立Ontology](https://www.douyin.com/video/7298014998062714121)
- [bilibili: Ontology Practice - Build pizza.owl in Protégé](https://space.bilibili.com/158390142/lists/2469670?type=season)

对应版本的GitHub建模仓库是：https://github.com/yasenstar/protege_pizza

在国内平台上我收到不少朋友的反馈，说一方面教程本身内容是英文的，另一方面我的视频内容与解说也是英文的，听起来和理解起来不是很方便。

本人自己在过去一段时间对本体、知识图谱等的学习过程中，尤其是对Protégé(本体编辑器)的建模使用的体会中，也深感纯中文的参考内容还是很缺乏，所以这个建模仓库我计划从纯中文的角度来重新诠释这个pizza.owl的教程的内容，并据此重新录制完全中文的演示视频。

希望通过自己的努力，能够向大家分享更加易于接触与学习理解的本体建模的理论和工具技能，让本体和知识图谱的概念更加发展壮大。

欢迎大家在讨论区提出你的宝贵意见和建议。

## 教程文档

更新的v3.2英文版本你可以在我的英文github仓库中找到（链接上面已经提供），我也复制放到了本仓库的docs目录中，这是[直接链接](./docs/Protege%205%20New%20OWL%20Pizza%20Tutorial%20V3.2.pdf)。

在演示准备的过程中，我会同步将其翻译到中文版本并分章节列出，同时建模的文件也会安装每个示例保存对应的快照，以方便大家学习时可以直接跳转到某一个位置，这个方式是和我处理英文版的演示视频与模型对应关系是一样的。

## 文档结构

![protege-ontology-toc](./img/pizza-ontology-toc.png)

| | | | |
| --- | --- | --- | --- |
| [第01章](./第01章/README.md) | [第02章](./第02章/README.md) | [第03章](./第03章/README.md) | [第04章](./第04章/README.md) |
| [第05章](./第05章/README.md) | [第06章](./第06章/README.md) | [第07章](./第07章/README.md) | [第08章](./第08章/README.md) |
| [第09章](./第09章/README.md) | [第10章](./第10章/README.md) | [第11章](./第11章/README.md) | [第12章](./第12章/README.md) |
| [第13章](./第13章/README.md) | [第14章](./第14章/README.md) |  |  |

## 各章节内容简介

| 章节 | 基本内容 |
| --- | --- |
| 01 | 介绍使用许可证，和使用在文档中的相关命名规则 |
| 02 | 介绍了文档的需求，并对Protégé的用户界面加以描述 |
| 03 | 提供了OWL本体语言的简单描述 |
| 04 | 实际建立一个OWL本体，包含类和对象属性；并使用描述逻辑推理机来检查本体的一致性和对本体类层级进行自动计算 |
| 05 | 描述了数据属性 |
| 06 | 描述了本地的设计模式，并演示了其中一种模式：向一个枚举类添加排序 |
| 07 | 描述了关于OWL实体名称的多种概念 |
| 08 | 介绍了基于前面7章建立的披萨本体的扩展版本，后续章节将使用此扩展版本来练习和演示写入规则，进行查询，和定义约束 |
| 09 | 介绍了进行查询的两种工具：描述逻辑查询和SPARQL查询 |
| 10 | 介绍了语义网规则语言（SWRL），并演示创建SWRL和SQWRL规则 |
| 11 | 介绍了形状约束语言（SHACL），并探讨了描述逻辑中的逻辑公理与SHACL中的数据完整性约束的不同 |
| 12 | 谈论了一些结论、想法和观点 |
| 13 | 参考文献 |

---

Good Luck!