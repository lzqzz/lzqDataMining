# lzqDataMining
## 创建新的仓库
命名为lzqDataMining 初始化时Add a Readme file

## 上传ppt
1.首先在本地建一个文件用于`git clone`操作，将创建的仓库文件克隆到本地

`git clone https://github.com/lzqzz/lzqDataMining.git`

2.将需要上传的文件拖入本地仓库

3.打开终端，使用 git add 命令将文件添加到暂存区

`git add DNA存储.pptx`

4.使用 git commit 命令提交更改到本地仓库

`git commit -m "Add DNA存储.pptx"`

5.使用 git push 命令将更改推送到远程仓库

`git push origin main`

如果你使用的是旧的仓库，可能需要将 main 替换为 master，并保证你的令牌没有过期，如果过期需要在github网站上更新你的令牌

## 相关计算机技能学习
### 背景介绍
DNA存储方向，数据可视化和图形化工具的应用可以是一个非常有用的技能。数据可视化是将抽象的数据转换为可视化形式的过程，能够帮助研究人员更好地理解和分析数据。在DNA存储领域，通过数据可视化可以直观地展示DNA序列、存储效率、错误率等重要信息，有助于评估和优化DNA存储系统的性能。图形化工具可以用于可视化DNA序列的结构和特征，包括碱基组成、序列长度、GC含量等；展示DNA存储系统的性能指标，例如存储密度、读取速度、错误率等

### 相关技能
在DNA存储研究中，Matplotlib和Seaborn作为Python中主要的数据可视化库，扮演着关键的角色。它们提供了丰富的功能和灵活的工具，帮助研究人员创建各种类型的图形来呈现生物数据，包括散点图、折线图、箱线图、热图等。

#### Matplotlib：

Matplotlib是Python中最流行的绘图库之一，提供了广泛的功能和灵活的绘图选项。它可以用来创建各种类型的图形，包括基本图形如折线图、散点图、柱状图，以及高级图形如3D图形、轮廓图等。

在DNA存储研究中，Matplotlib可以用来呈现各种生物数据，比如：

- DNA序列的碱基组成分布图，帮助分析DNA序列的特征和结构；
- DNA存储系统的性能指标如存储密度、错误率等的折线图，帮助评估系统性能的变化和趋势；
- 不同DNA编码方案的比较箱线图，帮助研究人员选择最优的编码方案。

#### Seaborn：

Seaborn是基于Matplotlib的Python可视化库，专注于统计数据可视化，提供了更高级的绘图功能和更美观的默认样式。

在DNA存储研究中，Seaborn可以用来创建更具有统计意义的图形，比如：

- DNA序列的热图，用于展示不同区域的碱基组成和相似性；
- DNA存储系统中不同条件下性能指标的分布散点图，帮助分析性能数据的相关性和趋势；
- DNA编码方案的效率比较箱线图，配合统计分析功能进行显著性检验。

### 技能学习

#### 基础知识学习阶段（1-2周）：
- 学习Matplotlib和Seaborn的基本语法和常用功能。
- 完成一些简单的数据可视化练习，如绘制散点图、折线图等。

#### 进阶技术学习阶段（2-4周）：
- 深入学习Matplotlib和Seaborn的高级功能，如子图、标签、颜色映射等。
- 学习使用Seaborn进行统计分析可视化，如热图、箱线图等。
- 完成一些较复杂的数据可视化项目，如生物数据的可视化分析。

#### 实践项目阶段（4-6周）：
- 选择一个相关领域的实际项目，如DNA存储相关数据的可视化分析。
- 应用所学知识，使用Matplotlib和Seaborn创建项目所需的各种图形。
