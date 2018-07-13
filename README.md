# AIPND-cn-trial

## 安装

### Step 1 安装Anaconda环境

首先我们需要在Windows系统上安装Anaconda环境，到[官网](https://www.anaconda.com/download)选择一个版本下载，建议选择Python3.6版本，如下图所示：

![](./imgs/ana1.png)

点击运行

![](./imgs/ana2.png)

点击next

![](./imgs/ana3.png)

点击I Agree

![](./imgs/ana4.png)

选择All Users，点击Next

![](./imgs/ana5.png)

选择安装目录，注意**目录路径不要有中文**，否则容易出现意想不到的错误

![](./imgs/ana6.png)

这里全部勾选，点击Install

![](./imgs/ana7.png)

安装过程中，请稍候

![](./imgs/ana8.png)

全部勾选，完成安装

![](./imgs/ana9.png)

安装完成后在开始菜单中能看到Anaconda项

![](./imgs/ana10.png)

打开上图中的“Anaconda Prompt”，使用CD命令切换到项目源代码所在目录，比如我这里将项目放到了D盘的AIPND-cn-trial-master目录下，那么就使用如下命令进入该目录：

首先切换到D盘，然后进入代码所在目录

输入`d:`然后回车

输入`cd AIPND-cn-trial-master`然后回车

![](./imgs/ana11.png)

**请学员根据自己存放代码的具体位置修改上述命令**

紧接着，使用pip命令，根据项目目录中的requirements.txt安装所需软件包，这些软件包都是通过Python标准包管理工具pip管理的，Anaconda环境可直接使用。

`pip install -r requirements.txt`

![](./imgs/ana12.png)

最后，使用conda命令，安装wordcloud软件包，该软件包只能在Anaconda环境（notebook或ipython）中使用。

`conda install -c conda-forge wordcloud`

![](./imgs/ana13.png)

遇到`Proceed ([y]/n)?`，输入y然后回车

![](./imgs/ana14.png)

下载和安装软件包过程中，请稍候

![](./imgs/ana15.png)

下载完成后，在终端中输入以下命令然后回车，稍等片刻，就可以在打开的浏览器窗口中开始实战项目了！

`jupyter notebook "My Wechat Friends.ipynb"`

