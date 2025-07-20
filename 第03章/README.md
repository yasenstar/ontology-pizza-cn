# 第03章 OWL本体的定义

本体(Ontology)用来抓取某些感兴趣领域(domain of interest)的知识。一个本体模型既描述了这个领域中的概念(concepts)，也描述了存在于这些概念直接的关系(relationships)。

不同的本体语言提供了不同的实现方式，在标准化本体语言中最近开发的是出自World Wide Web Consortium (W3C)的OWL - Ontology Web Language。

参考 https://www.w3.org/TR/owl2-primer/ ： OWL是一种语义网语言，设计用来表示关于事物(thing)、事物组以及其中的关系的富和复杂的知识。(Standard definition in English in owl2-primer: The W3C OWL 2 Web Ontology Language (OWL) is a Semantic Web language designed to represent rich and complex knowledge about things)，此文件的本地版本请从[这里](../docs/owl2-primer.pdf)下载。

OWL，基于集合论和逻辑论，使得明确无歧义的对概念进行描述成为可能。复杂的概念可以经由比较简单的概念来逐步建立起来。逻辑模型允许使用推理机，其机制能够检查本体中是否所有的论点和定义都是一致的，并且识别出哪个概念服务于哪个定义。进一步的，推理机可以帮助维护正确的本体层级结构。这个机制特别的对于那些具有多个父类的类的情形非常有帮助。推理机也可以推断出一些额外的信息。例如，如果两个属性是互逆(inversed)的，那么只有其中一个需要用户的断言(assertd)，然后推理机则会自动推断出反向的属性。

## 3.1 OWL本体中的组件

一个OWL本体包含类(classes)，属性(properties)，和个体(individuals)。

- 一个类是一个集合
- 一个属性是一个二元关系
- 一个个体是集合中的一个元素

OWL本体是由描述逻辑(Description Logic - DL)来实现的，DL是一阶逻辑(First Order Logic)的可判定的(decidable)的子集。

其他来自于集合论中的概念也在OWL中有所实现，如不相交的集合(Disjoint set)，空集合(the Empty set - owl:Nothing)，逆关系(inverse relation)，传递关系(transitive relation)，等等。

对集合论中的基本概念有所了解将能够帮助用户理解OWL中的大部分概念，但是这并不是必须的。在这方面，使用Protégé的一个显著的好处是其提供了直观的用户界面来是领域专家们不需要集合论的知识背景就能够定义本体模型。然而，对于开发人员来说，还是希望能够复习回顾一些逻辑论和集合论的知识。

下面的链接中 Overview of Set Theory 的前三章可以作为一个很不错的参考：

https://www.michaeldebellis.com/post/owl-theoretical-basics

这里是[Overview of Set Theory节选的本地版本](Partee%20et%20al.pdf)

---

[<button type="button">«第02章</button>](../第02章/README.md) [<button type="button">第04章»</button>](../第04章/README.md)

[<button type="button">HOME</button>](../README.md)