# data_structure

1 什么是数据结构
  数据结构是相互之间存在一种或多种特定关系的数据元素的集合。

2 基本概念和术语
2.1 数据
  数据：是描述客观事物的符号，是计算机中可以操作的对象，是能够被计算机识别，并输入给计算机处理的符号集合。
2.2 数据元素
  数据元素：是组成数据的、有一定意义的基本单位，在计算机中通常作为整体处理。也被称为记录。
2.3 数据项
  数据项：一个数据元素可以由若干个数据项组成。数据项是数据不可分割的最小单位。
  三者的关系：数据由数据元组构成，而数据元素又由若干个数据项组成。
2.4 数据对象
  数据对象：是性质相同的数据元素的集合，是数据的子集。
2.5 结构
  结构：不同数据元素之间不是独立的，而是存在特定的关系，这种关系被称作结构。

3 结构
  结构用于描述数据对象中数据元素之间的某种关系，分为逻辑结构和物理结构。
3.1 逻辑结构
  逻辑结构：是指数据对象中数据元素之间的相互关系（逻辑上的关系或一种表现形式上的关系）。逻辑结构可以划分为下面的四种：
  集合结构：集合结构中的数据元素除了同属于一个集合外，它们之间没有其他关系。
  线性结构：线性结构中的数据元素之间是一对一的关系。
  树形结构：树形结构中的数据元素之间存在一种一对多的层次关系。
  图形结构：图形结构中的数据元素之间是多对多的关系。
  逻辑结构是针对具体问题的，是为了解决某个问题，在对问题理解的基础上，选择一个合适的数据结构来表示元素之间的逻辑关系，
  有助于对具体问题的解决。
3.2 物理结构
  物理结构/存储结构：是指数据的逻辑结构在计算机中的存储形式。
  数据的存储结构应正确反映数据元素之间的逻辑关系，这才是最为关键的，如何存储数据元素之间的逻辑关系，是实现物理结构的重
  点和难点。数据元素的存储结构形式有两种：顺序存储和链式存储：
  顺序存储结构：是把数据元素存放在地址连续的存储单元里，其数据元素间的逻辑关系和物理关系是一致的。
  优点：便于随机存取数据元素，适合数据不经常发生变化的情况；
  缺点：不利于数据元素的删除和增加，需要移动数据元素。
  链式存储结构：把数据元素存放在任意的存储单元里，这组存储单元可以是连续的，也可以是不连续的。数据元素的存储关系并不能
  反映逻辑关系，需要借助于其他辅助信息。

  逻辑结构是面向问题的，而物理结构是面向计算机的，其基本目标就是将数据元素及其逻辑关系存储到计算机的内存中。
