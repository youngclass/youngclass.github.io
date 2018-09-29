# 配置 Visual Studio Code 练习 C 语言

## 安装 VS Code

下载安装 [Visual Studio Code](https://code.visualstudio.com/) 是很简单，一路默认下一步，就安装好了。从菜单里找到应用，点击打开，就会看到下面这个欢迎界面，酷酷的。

![欢迎界面](./img/vscode-start-02-open-vscode.png)

但是，都是英文，(⊙o⊙)…
好吧，要好好学习英语。当然，我们也可以配置一下语言，目前，我觉得英文界面也没什么难的。

界面的左边是一个工具栏，上面有 5 个图标。好像很高大上的样子，先不去动它。嗯嗯，看到 *Start* 那边有一个 *New file*。好，那就先新建一个文件看看。（我们也可以通过File->New File 或者按 Ctrl-N 来新建一个文档。）

保存成 test.c，老师说可以先试试。
然后，vscode 右下角提示我装什么 C/C++ 插件。嗯嗯，提示的东西一般不错，我们按推荐安装，点击 install。没有出来这个提示的同学不要着急，我们有两种方法来自己安装 C/C++ 插件：

- 方法1：点击左下角的齿轮形状按钮（实际上是菜单功能），点击里面出来的 Extentions 
- 方法2：直接点击最左侧 5 个按钮中最后那个方形拼图按钮

这两种方法都会打开“EXTENTIONS”卡片：

![C/C++扩展](./img/vscode-start-03-c-extention.png)


然后我们点击 *RECOMMENDED* 下面的 *C/C++* 插件的 install 按钮进行安装，于是，我们的 vscode 就具备了 C/C++ 的基本功能。注意，这个工具是 Microsoft 提供的一个扩展，可以认为是 vscode 最可靠的扩展之一吧。

下面我们可以继续愉快地写代码啦，写一个 hello, world 吧。

```C
#include <stdio.h>

int main() {

  printf("Hello, World!\n");
  return 0;
}
```

大家记得遵循 C 语言的新标准来写标准的代码~~

到目前为止，一切都很好。可是，可是... 我要按编译按钮了，在哪里？在哪里？


![配置所需的两款工具](./img/vscode-start-01-prepare-downloads.png)

- [MingGW]: 在 Windows 环境下的最小 GNU 工具集。包含了基本的 C 语言函数库，gcc 编译器集合。这个是骨架。
- [Visual Studio Code]