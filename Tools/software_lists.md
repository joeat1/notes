# Windows 软件安装列表

> C盘主要放置系统和基础环境，一般软件全部安装在D盘。

- [Windows 软件安装列表](#windows-软件安装列表)
  - [编辑器](#编辑器)
  - [虚拟机](#虚拟机)
  - [编程环境](#编程环境)
  - [常用程序](#常用程序)
  - [远程连接](#远程连接)

## 编辑器

+ [Sublime](https://www.sublimetext.com/)    

  + **添加一下内容到 hosts 文件 （Windows系统在 C:\Windows\System32\drivers\etc 下面）**
    ```hosts
    127.0.0.1 www.sublimetext.com
    127.0.0.1 license.sublimehq.com
    ```

  + 注册码 http://www.codejie.net/3555.html

    ```
    TwitterInc
    200 User License
    EA7E-890007
    1D77F72E 390CDD93 4DCBA022 FAF60790
    61AA12C0 A37081C5 D0316412 4584D136
    94D7F7D4 95BC8C1C 527DA828 560BB037
    D1EDDD8C AE7B379F 50C9D69D B35179EF
    2FE898C4 8E4277A8 555CE714 E1FB0E43
    D5D52613 C3D12E98 BC49967F 7652EED2
    9D2D2E61 67610860 6D338B72 5CF95C69
    E36B85CC 84991F19 7575D828 470A92AB
    ```

  + 设置当前文件自动换行：view——》Word Wrap，设置全局 ：在preferences中选择setting，在用户设定中加入`"word_wrap": true`

  + 常用插件 

    > 按下Ctrl+Shift+P调出命令面板

    + **DocBlockr** 与 **DocBlockr python**  注释插件，标准的注释，包括函数名、参数、返回值等
    + **Ctags**           函数跳转，Alt+点击 函数名称，会跳转到相应的函数
    + **FileDiffs**      强大的比较代码不同工具
    + Anaconda    配合python环境使用
    + SublimeCodeIntel    代码提示和补全插件，安装该插件后需要根据您使用的编程语言进行配置
    + SublimeLinter   代码中存在的不规范和错误的写法的检查插件，需要配置相应语言的环境
    + **PlainTasks**           超棒的待办事项列表，可以创建项目，分配标签，设置日期
    + **SublimeREPL**      直接在编辑器中运行适用于许多许多语言的解释程序
    + [Latextool](https://latextools.readthedocs.io/en/latest/)            便于latex文件的操作

+ Vscode

  + **TabNine**  基于GPT-2语言模型的自动补全工具
  + **TODO Highlight**   突出显示我们还有哪些内容有待完善 常用的待办标记有`TODO`和`FIXME`
  + **Code Runner**  主流编程语言快速运行的插件 
  + `latex-workshop` 写latex需要使用
  + Markdown all in one  功能很齐全，`- [x] Finish my changes`可以表示任务列表

+ [Markdown编辑器：typroa](https://typora.io/) 
+ [ Latex编辑器：TeXstudio](http://texstudio.sourceforge.net/)
  + [MikTex basic版本](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/windows/miktex/setup/windows-x64/) Latex环境


## 虚拟机

+ [Vmware](https://www.vmware.com/cn/products/workstation-pro/workstation-pro-evaluation.html) 

  + 注册码

  ```
  VMware Workstation 15 for Windows
  UA5DR-2ZD4H-089FY-6YQ5T-YPRX6
  ZF582-0NW5N-H8D2P-0XZEE-Z22VA
  GA590-86Y05-4806Y-X4PEE-ZV8E0
  UG5J2-0ME12-M89WY-NPWXX-WQH88
  YA18K-0WY8P-H85DY-L4NZG-X7RAD
  ```


## 编程环境
  

+ [python环境 Anaconda](https://www.anaconda.com/)  

  + [换conda源](https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/) 
  + pip换源： `pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple` 
  + 离线安装 `conda install XXX.tar.bz2`        选定环境`-n ENVIRONMENT` 



## 常用程序

+ [有道词典](http://cidian.youdao.com/) 

  + 截屏翻译 快捷键：Ctrl + Alt + D

+ [谷歌浏览器](https://www.google.cn/chrome/index.html) 

  + 插件：油猴

+ [7Z](https://www.7-zip.org/)    压缩与解压 

## 远程连接

+ TeamViewer