# COMP2014 - C++语言程序设计

![Static Badge](https://img.shields.io/badge/%E8%80%83%E6%9F%A5%E8%AF%BE-green)
![Static Badge](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-2-moccasin)
![Static Badge](https://img.shields.io/badge/拓展选修课-purple)

![Static Badge](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![Static Badge](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A-20%25-wheat)
![Static Badge](https://img.shields.io/badge/%E5%AE%9E%E9%AA%8C-40%25-wheat)
![Static Badge](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-40%25-wheat)

## 课程简介（摘自教学大纲）

本课程是机械类、自动化类及相关专业的专业选修课，可用于数据处理、数值计算和系统程序设计等领域。通过本课程的学习，使学生系统地掌握面向对象设计的思维方式、基本概念与基本方法，达到熟练运用 C++ 语言进行面向对象程序设计、解决实际应用问题的目的。

课程主要内容包括：
1. C++ 语言相比于 C 语言的新特征；
2. 介绍容器与算法的概念与应用；
3. 类与数据抽象的概念与使用方法；
4. 介绍模板与泛型编程；
5. C++ 编程规范；
6. 开发 Windows 应用程序的方法与技巧。

## 授课教师

- 王焦乐
  - 授课风格：PPT + 课堂上使用 VSCode 演示代码
  - 听课建议：由于课后会发PPT，因此只需在课后按照PPT中的内容上网搜索相关资料即可。
  - `C++` 本是一个工具，你为什么要像准备一门考试一样地学习它呢？

## 作业/实验

作业都非常简单，~~尤其是有了 AI 的帮助后~~，即给出几个任务写出对应的程序，然后在作业中展示代码和运行结果即可。

实验则相对麻烦，每次会给一个内容较多的任务，在一两个星期内完成。然而每次实验课都要在机房坐一个下午（很多人不会去或者中途润），并且会考勤。

虽然每次实验任务都是大工程，然而无论是高级语言程序设计还是这门课都没有教大家使用**多文件**。
有兴趣的朋友建议自己学习一下，这样可以让代码更加清晰，也更加符合工程化的思想。

- [longlin 的 cpp 实验仓库](https://github.com/longlin10086/HITSZ-cppLab)
- [Maxwell Jay/CppLab_2023](https://github.com/MaxwellJay256/CppLab_2023)

## 关于考试

2023 年的考试和 [高级语言程序设计](https://hoa.moe/docs/fresh-autumn/comp1011/) 类似，考试内容为 选择 + 填空 + 手写编程题（又是你校喜闻乐见的手写代码环节）。
选择与填空是非常死板的考察 C++ 语言的知识点；编程题比较简单，与实验课的内容相似。

整体难度不大，但……

- 题目还在使用 N 年前的 cpp 标准，部分题目在新标准下无解，而试卷却无明确提示使用何种 cpp 标准
- 题目完全没有考察意义，甚至出现某些题目单纯考「 这被称作____ 」
- 重复手写极长变量名
- ……

## 学习建议

都什么年代，还在写传统 cpp ，是时候拥抱摩登 cpp 了。当前项目业务开发，已经没有那种死守c11标准不动的老古董了，而且你校的教学甚至连 c11 标准都达不到，令人感叹。

下面提供我个人的 cpp 学习路线，以供参考：
- 通过 [Cherno 的cpp系列](https://www.youtube.com/@TheCherno) 了解 cpp 入门知识，GitHub 上也有相应的 [笔记](https://github.com/Nagi-ovo/Cherno-CPP-Notes)。
- 当某一环节十分不清楚时，优先在 [微软官方Morden CPP教程](https://learn.microsoft.com/zh-cn/cpp/cpp/welcome-back-to-cpp-modern-cpp) 对相应知识点进行查找。
- 如果微软官方文档仍然含糊其辞，表述不清，那就上 **知乎** 搜索相关问题，寻找相关优质回答。
- 如果上述所有方式都不能找到相关解答，只能硬啃 [cppreference](https://zh.cppreference.com/w/%E9%A6%96%E9%A1%B5)，或者在 **Google** 关键词搜索一条条查看了。

学习过程中最重要的是不断询问 「 为什么要有这样的新功能？这样做有什么好处？解决了什么问题？」，当你心中已不再有这类疑惑时，你才能算真正掌握了这块知识点，而不是填鸭式教育般给你灌输一堆不明所以的知识。

同时，学习编程还少不了代码实践，当你对某项知识出现疑惑时，不妨动手实践一番验证你内心的想法。

最后，多看看别人的优质代码，同样的功能，别人是怎么优雅实现的，如此这般你的代码水平才会有所提升。

> 文 / [longlin li](https://github.com/longlin10086), 2023.11

---

与 [高级语言程序设计](https://github.com/HITSZ-OpenAuto/COMP2021) 一样，作为一门编程语言，你本不应该像学习数学或者历史一样，用死磕书本和题目的方法学习 C++。

然而既然你选择了它，就不得不面对考试。但这是考查课 + 选修课，所以你其实没有那么多需要瞻前顾后的事情，尽管按照自己喜欢的方式学习 `C++` 吧。

说得夸张点，大家已经在自动化专业摸爬滚打一年了，玩「**技术流**」的学生根本不可能惧怕这门课。

> 文 / [Maxwell Jay](https://github.com/MaxwellJay256), 2023.11

## 推荐学习资料

- [Cherno 的 cpp 系列](https://www.youtube.com/@TheCherno)
- [微软官方 Morden CPP 教程](https://learn.microsoft.com/zh-cn/cpp/cpp/welcome-back-to-cpp-modern-cpp)
- [现代 C++ 教程：高速上手 C++ 11/14/17/20](https://changkun.de/modern-cpp/zh-cn/00-preface/)
- [cppreference](https://zh.cppreference.com/w/%E9%A6%96%E9%A1%B5)
- [mq白](https://github.com/Mq-b)
