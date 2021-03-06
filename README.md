# Cpp_Rust_Learn

# 缘由
2020-09-23 开始，经查阅资料后，决定开始自学 Rust 语言开发方向。在学习 Rust 之前，需要打牢 C++ 的基础。由于 C++ 体系庞大，因此暂先只计划 C++ 的学习路径。

**此仓库记录这个学习过程。**

# 基础情况
大学期间学习了 C 和 C++，但目前只会用 C 写一些简单的循环，C++ 则是连 a+b 都不会写，所以这次等于是从头开始一点点学。整体的学习路径大致是先看书，再刷题，然后是尝试实战。刷题使用的环境是 VS 2019。虽然很多人都不推荐 VS，但我认为那些文章已经老旧，VS 2019 安装快捷方便，对 C++ 初学者友好。

大四开始在一家医药研发公司做 IT 支持（可以粗暴理解为网管、运维，但这只是工作的 10% 不到），工作中比较常接触到的是计算机网络和操作系统的知识，编程也有，但比较少。因此我在制定书单顺序时，会在一开始比较艰难的时候，在几本厚厚的书中间穿插着几本计算机网络和操作系统的书籍。

# 学习路径
## 书单：（有先后顺序）
根据我个人的实际基础，制定了以下书单顺序。
* // 看书过程中会根据书上的练习、例子，编译相关项目练手。
* [《C++ Primer 第五版》](https://book.douban.com/subject/25708312/)
* [《TCP IP 详解 卷1：协议 第二版》](https://book.douban.com/subject/26825411/)
* [《TCP IP 详解 卷2：实现》](https://book.douban.com/subject/1087767/)
* [《TCP IP 详解 卷3：TCP事务协议、HTTP、NNTP和UNIX域协议》](https://book.douban.com/subject/1058634/)
* [《C++标准库 第二版》](https://book.douban.com/subject/26419721/)
* [《深入理解计算机系统 第三版》](https://book.douban.com/subject/26912767/)
* [《Effective C++ 第三版》](https://book.douban.com/subject/5387403/)
* [《C++语言的设计和演化》](https://book.douban.com/subject/1096216/)
* [《算法导论 第三版》](https://book.douban.com/subject/20432061/)
* [《算法 第四版》](https://book.douban.com/subject/19952400/)
* [《剑指Offer 第二版》](https://book.douban.com/subject/27008702/)
* // 此处停止看书，开始刷 LeetCode，刷到一定程度时，会（视情况决定是否有必要）学习并整体迁移至 Linux 开发环境，然后开始看下一本书。
* [《设计模式：可复用面向对象软件的基础》](https://book.douban.com/subject/1052241/)

## 学习设备 & 方法
首先是看书的“设备”。其实书单里很多书我在大学期间都买了，两年来也没有出新版。这些书都在家里，寄到单位来代价比较大，所以我这次选择了电子书。

学习电子书，需要有比较好的阅读设备，笔记本是肯定不行的。刚好我有台Surface Go，平时也不知道能干什么，性能极差，不过拿来看书和记笔记是极好的。**极力推荐传统 Edge 浏览器 + Onenote + Drawboard PDF 的组合，其中 Drawboard PDF 是看书主力，让你真的会有种看纸质书记笔记的感觉。** 需要注意的是，Drawboard PDF 的荧光标记在传统 Edge 下会被渲染为无透明度的直接覆盖，因此 Drawboard PDF 处理过的 PDF 最好不要使用传统 Edge 阅读，新版 Edge 倒是没问题（但是传统 Edge 打开书籍的速度秒杀新版）。

其次是编译的设备，就用普通的办公笔记本了，我的设备是 Magicbook 14 锐龙版。编译器选择是 [Microsoft Visual Studio 2019 社区版](https://visualstudio.microsoft.com/zh-hans/vs/)。

最后是学习方法，这里提几点：
* 第一，是英语还是中文的问题。个人建议，对于比较厚的书，中英文书籍都要备好，中文为主，中文看不懂、有歧义时，去看英文原文是什么。而对于比较短的书，英文为主，英文难以理解的，去看中文译者是怎么理解的。对于编译器，请一定不要头硬，如果你愿意选择 VS，那就一定要选择中文版。中文的各种提示和报错，对初学者不要太友好了。
* 第二，是看书方法的问题。我的习惯是，用黄色荧光笔标记下重要部分，用蓝色钢笔圈注疑问，当此疑问在后面的章节有解答，或者自己搜索到了答案时，在圈注上做序号标记，然后在页面底部解释此标记。每天开始时，要把昨天看过的内容总结提炼到 Onenote 中。

## 进度
查看整体进度，在本仓库的[项目](https://github.com/geeklihui/Cpp_Rust_Learn/projects)中。

目前的进度为：
* [C++ Primer 5th](https://github.com/geeklihui/Cpp_Rust_Learn/projects/1)
    - [Chapter 1](https://github.com/geeklihui/C-_Primer_Chapter1)
