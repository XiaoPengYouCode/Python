# Sublime Text 的安装和使用

## 一. 为什么不使用 windows 自带的文本编辑器写代码

首先大家已经看到, 用电脑自带的文本编辑器就能进行 Python 代码的编写, 而 Sublime Text 也是一个文本编辑器, 为什么要使用Sublime Text 呢. 

我们把 Sublime 这类的文本编辑器通常又称为代码编辑器, 它一般有以下优点

- 好看, 颜值即正义(bushi)

- 拥有一些针对写代码的强大的功能, 比如
  
  - 代码高亮, 不同类型的代码使用不同的颜色进行区分
  
  - 代码提示, 能够自动补全代码, 智能纠错, 智能提示, ........, 但是我们选择的 Sublime Text
  
  - 代码巡航, 真正写一个大项目的时候, 好多个文件的内容相互索引, 代码编辑器能够在这些文件中相互巡航索引
  
  - 文件管理, 代码编辑器通常都以一个文件夹为工作单位, 而不仅仅针对某个文件, 之后写项目的时候会有体会

- 现代的代码编辑器, 相比上面说的更上一层楼, 已经不局限于文本编辑, 拥有更多强大的功能, 例如
  
  - 集成开发环境, 能够在代码编辑器中进行代码的运行和调试
  
  - 版本控制, 这个之后有机会介绍, 也很重要
  
  - 可以安装插件, 扩展性强, 上面说的集成开发环境多半也是通过插件实现的
  
  - 花里胡哨的, 比如协同, 云开发, 等等

但是, 这类代码编辑器也有亿些缺点, 如

- 上手难度大, 学习成本高
  
  - 各种快捷键, 需要时间学习
  
  - 有些配置需要使用特殊的语言格式完成, 刚开始不适应
  
  - 丰富的扩展性意味着更高的学习成本

- 可能发生的各种 BUG

但是, 可以发现, 上面的缺点都是人的缺点, 不是编辑器的🐶

## 二. 为什么选 Sublime Text

代码编辑器其实也很卷的, 五花八门, 各显神通, 比较常见的有

- VS Code
  
  - 地表最强, 微软出品

- Sublime Text

- Atom
  
  - VS Code 的前身, Github 出品, 之前一家独大, 后来 Github 被金主爸爸微软收购了, 于是 Atom 的特性被渐渐移植到了 VS Code 上, Atom 渐渐就寄了, 现在已经不维护了

- notepad++
  
  - 曾经地表最强, 但是时代变了, 但是在打开大文件方面依旧有优势

- Vim / Neo Vim
  
  - Vim 是一代传奇, 老程序员和极客的最爱, 主要用在 Linux 系统, VS Code 可以通过插件实现 Vim 的编辑方式
  
  - Vim 上手难度非常高

- Emacs
  
  - 另一代传奇, 开发者 理查德•斯托曼 被称为自由软件之父, 也是老程序员比较喜欢的

- 各种集成开发环境中都有编辑器
  
  - 集成开发环境就是 写代码, 运行和调试放在一起的一个庞大的工具

- 还有好多, 不一一列举了, 有的文本编辑器或者继承环境一般是针对特定语言的

后期我们可能会接触到 VS Code, 可能性比较大, 毕竟地表最强, 但是现在我们先用 Sublime Text, 它的优点是

- 比较轻量化

- 我也不知道了

相比 VS Code, Sublime Text 貌似没有什么优点, 除了轻量化

## 三. Sublime 的下载和安装

首先 Sublime 是一个收费软件, `99$` 终身买断制, 但是这个软件有一个比较奇怪的设定, 就是不买也可以一直试用, 没有期限

因为我现在在火车上没有网, 所以安装的过程我就不演示了, 大致是

- 打开 Sublime Text 的<mark>官网</mark>, 之后教大家如何优化浏览器的使用体验

- 下载

- 安装, 尽量也是在 D 盘专门为 Sublime Text 单独创建一个文件夹

- 打开使用

关于书上 `1.3.1` 章节的配置, 不配置应该也可以, 直接使用快捷键 `Ctrl + B` 就能运行 Python 代码

你们可以用 `print("Hello World!")` 测试一下, 因为我这边已经配置了, 不知道怎么回去, 但是我觉得不配置也可以, 你们试一下, 如果不能正确运行的话就配置一下, 配置也挺简单的, `1.3.1` 章节有


