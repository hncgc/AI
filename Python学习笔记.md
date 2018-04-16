# Python学习笔记  

安装Pathon 3.6.4
---

[Python 3.6.4](https://www.python.org/downloads/release/python-364/)  

> 安装位置：C:\Users\Administrator\AppData\Local\Programs\Python\Python36

将C:\Users\Administrator\AppData\Local\Programs\Python\Python36 添加到Windows 环境变量Path

C:\Users\Administrator>path C:\ProgramData\Oracle\Java\javapath;%SystemRoot%\sys
tem32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPower
Shell\v1.0\;C:\Program Files\Java\jdk1.8.0_101\bin;C:\Users\Administrator\AppDat
a\Local\Programs\Python\Python36

C:\Users\Administrator>python -v

C:\Users\Administrator>python -v

C:\Users\Administrator>

无法启动程序，因为计算机中丢失
api-ms-win-crt-runtime-|1-1-0.dll。偿试重新安装该程序以解决此问题。

[丢失api-ms-win-crt-runtime-l1-1-0.dll咋办？](https://jingyan.baidu.com/article/5bbb5a1b07fb6e13eba179bc.html)  
> api-ms-win-crt-runtime-l1-1-0.dll 32/64位  
> http://www.xue51.com/soft/2147.html
```
1、下载本站提供的api-ms-win-crt-runtime-l1-1-0.dll。
2、直接拷贝该文件到系统目录里：
C:\Windows\System32目录下，64位系统为：C:\Windows\SysWOW64
3、最后在开始菜单中找到“运行(R)” 或者按快捷键“Win+R”，在弹出的框内输入“regsvr32 api-ms-win-crt-runtime-l1-1-0.dll”(不含双引号)，回车即可解决错误提示！
```
pip安装
---

[pip安装](https://pip.pypa.io/en/latest/installing/)  
> To install pip, securely download get-pip.py. [1]:
> https://bootstrap.pypa.io/get-pip.py
```
get-pip.py拷贝到C:\Users\Administrator\AppData\Local\Programs\Python\Python36\Scripts
双击get-pip.py或在cmd下
C:\Users\Administrator\AppData\Local\Programs\Python\Python36\Scripts>python get-pip.py
运行结果：下载
easy_install.exe
easy_install-3.6.exe
pip.exe
pip3.6.exe
pip3.exe
wheel.exe
到C:\Users\Administrator\AppData\Local\Programs\Python\Python36\Scripts
```
[pip安装](https://pip.pypa.io/en/stable/installing/)  
> https://github.com/pypa/pip
> https://edu.tv.sohu.com/play/sid/f031a6c300ece0d9
```
C:>python
>>>
>>>exit()
C:>
```

使用Anconda安装python2.7
---

http://continuum.io/downloads  

交互式运行（在Widows平台下有 ipython notebook）

## jupyter

[致Python初学者们 - Anaconda入门使用指南](https://www.jianshu.com/p/169403f7e40c)  

[Jupyter notebook 安装，初步使用](https://www.cnblogs.com/wrajj/p/5676705.html)  

[左手程序员，右手作家：你必须会的Jupyter Notebook](http://python.jobbole.com/87527/?repeat=w3tc)  


[python入门基础视频](https://edu.tv.sohu.com/play/sid/ba815508527b07ef)  

[Python IDLE](IDLE 是一个纯 Python 下自带的简洁的集成开发环境(IDE)。



Anaconda
---

[致Python初学者们 - Anaconda入门使用指南](https://www.jianshu.com/p/169403f7e40c)  

#### Anaconda3.5.1.0安装

[Download Anaconda Distribution](https://www.anaconda.com/download/)  
https://repo.continuum.io/archive/Anaconda3-5.1.0-Windows-x86_64.exe
> 下载很费时，要几个小时

[清华大学软件镜像站 Anaconda 镜像使用帮助](https://mirror.tuna.tsinghua.edu.cn/help/anaconda/)  
```
Anaconda 是一个用于科学计算的 Python 发行版，支持 Linux, Mac, Windows, 包含了众多流行的科学计算、数据分析的 Python 包。
Anaconda 安装包可以到 https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/ 下载。

```

C:\ProgramData\Anaconda3

开始 -> 程序 -> Anaconda3 (64bit) -> jupyter Notebook

C:\ProgramData\Anaconda3\python.exe C:\ProgramData\Anaconda3\cwp.py C:\ProgramData\Anaconda3 C:\ProgramData\Anaconda3\python.exe C:\ProgramData\Anaconda3\Scripts\jupyter-notebook-script.py %USERPROFILE%

http://localhost:8888/tree

C:\ProgramData\Anaconda3\Scripts
jupyter notebook

F:\AI>set path=%path%;C:\ProgramData\Anaconda3\Scripts

[Jupyter Notebook 快速入门](https://www.cnblogs.com/nxld/p/6566380.html)  

Shift + Enter 运行代码单元格

计算整个 notebook，只要点击Cell -> Run all

Matplotlib 是一个用于创建漂亮图形的 Python 库

[Python·Jupyter Notebook各种使用方法](http://blog.csdn.net/liuyanlin610/article/details/76231958)  

#### 更改Jupyter notebook的工作空间
```
在cmd中输入jupyter notebook --generate-config
如果该配置文件已经存在，那么，会出现如下信息,从中可以见到配置文件存在的位置
在其配置文件jupyter_notebook_config.py中，找到
# The directory to use for notebooks and kernels.
# c.NotebookApp.notebook_dir = ''
c.NotebookApp.notebook_dir = 'F:\python\test'   # error
c.NotebookApp.notebook_dir = 'F:/python/test'

C:\Users\Administrator>jupyter notebook --generate-config
Writing default config to: 
C:\Users\Administrator\.jupyter\jupyter_notebook_config.py
```
[python视频](https://edu.tv.sohu.com/play/sid/f031a6c300ece0d9)  
https://edu.tv.sohu.com/  

[全套Python基础视频 从基础到精通](https://edu.tv.sohu.com/course/0dca81b7b8c3745a)  

## Pycharm安装

https://www.jetbrains.com/pycharm/download/#section=windows  

```
https://www.jetbrains.com/pycharm/download/#section=windows
pycharm-community-2017.3.4.exe 社区版免费
pycharm-professional-2017.3.4.exe 专业版收费
社区版安装
C:\Program Files\JetBrains\PyCharm Community Edition 2017.3.4
启动
"C:\Program Files\JetBrains\PyCharm Community Edition 2017.3.4\bin\pycharm64.exe"

python3在线编辑解释器
http://www.runoob.com/try/runcode.php?filename=HelloWorld&type=python3
```
[Python学习手册(第4版) 原版清晰PDF带书签目录](http://www.linuxidc.com/Linux/2016-07/133286.htm)  
Linux公社FTP: ftp://ftp1.linuxidc.com/  
```
FTP地址：ftp://ftp1.linuxidc.com
用户名：ftp1.linuxidc.com
密码：www.linuxidc.com
在 2016年LinuxIDC.com\7月\Python学习手册(第4版) 原版清晰PDF带书签目录\
```
[Home/2017年资料/4月/3日/人工智能（AI）程序设计（面向对象语言）PDF+PPT与习题等/](https://linux.linuxidc.com/index.php?folder=MjAxN8Tq18rBzy801MIvM8jVL8jLuaTWx8Tco6hBSaOps8zQ8snovMajqMPmz/K21M/z0+/R1KOpUERGK1BQVNPrz7DM4rXI)  

[Python socket cs远程命令执行案例](https://linux.linuxidc.com/index.php?folder=MjAxN8Tq18rBzy8z1MIvMTTI1Q==)  

[Home/2017年资料/3月/10日/精通Python设计模式 高清晰PDF+源码/](https://linux.linuxidc.com/index.php?folder=MjAxN8Tq18rBzy8z1MIvMTDI1S++q82oUHl0aG9uyei8xsSjyr0guN/H5c76UERGK9S0wus=)

[Home/2017年资料/2月/10日/](https://linux.linuxidc.com/index.php?folder=MjAxN8Tq18rBzy8y1MIvMTDI1Q==)  

[Home/2017年资料/2月/10日/利用Python脚本获取Windows和Linux的系统版本信息/](https://linux.linuxidc.com/index.php?folder=MjAxN8Tq18rBzy8y1MIvMTDI1S/A+9PDUHl0aG9uvcWxvrvxyKFXaW5kb3dzus1MaW51eLXEz7XNs7Dmsb7Qxc+i)  

[Home/pub/Android源码集锦/](https://linux.linuxidc.com/index.php?folder=cHViL0FuZHJvaWTUtMLrvK+99Q==)  


Visual studio code
---

[Visual studio code下载](https://code.visualstudio.com/)  

[Visual studio code](https://baike.baidu.com/item/visual%20studio%20code/17514281?fr=aladdin)  

[Visual Studio Code使用心得](https://blog.csdn.net/jiangwei0512/article/details/52079031)  

[学会用好 Visual Studio Code](https://blog.csdn.net/GarfieldEr007/article/details/54619959)  

[初试Visual Studio Code配置Python开发环境](https://blog.csdn.net/tntnaoh/article/details/51173528)  

[Visual Studio Code + python 开发环境搭建](https://blog.csdn.net/weixinhum/article/details/73038117)  

[用VSCode写python的正确姿势](https://blog.csdn.net/u013597671/article/details/77693180)  

[Visual Studio Code配置PHP开发环境](https://blog.csdn.net/vezn_king/article/details/75453717)  


















