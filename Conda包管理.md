Conda包管理

[Conda介绍](https://blog.csdn.net/koflance/article/details/78582737)  

[Conda安装教程](https://conda.io/docs/user-guide/install/index.html#installing-conda-on-a-system-that-has-other-python-installations-or-packages)  
```
C:\Users\Administrator>conda -V
conda 4.4.10

C:\Users\Administrator>
```
[Anaconda+用conda创建python虚拟环境](https://blog.csdn.net/anyao_/article/details/79049937)  

[ 用conda创建python虚拟环境](https://blog.csdn.net/lyy14011305/article/details/59500819)  

[conda设置Python虚拟环境](https://blog.csdn.net/Co_zy/article/details/77412610)  
> 检查以查看哪些版本的Python可供我们使用：
> conda search "^python$"
```
C:\Users\Administrator>conda search "^python$"
Loading channels: done
Name                       Version                   Build  Channel
python                     2.6.8                         5  defaults
python                     2.6.8                         6  defaults
python                     2.6.9                         0  defaults
python                     2.6.9                         1  defaults
python                     2.7.3                         2  defaults
python                     2.7.3                         3  defaults
python                     2.7.3                         4  defaults
python                     2.7.3                         5  defaults
python                     2.7.3                         6  defaults
python                     2.7.3                         7  defaults
python                     2.7.4                         0  defaults
python                     2.7.5                         0  defaults
python                     2.7.5                         1  defaults
python                     2.7.5                         2  defaults
python                     2.7.6                         0  defaults
python                     2.7.6                         2  defaults
python                     2.7.7                         0  defaults
python                     2.7.7                         1  defaults
python                     2.7.7                         2  defaults
python                     2.7.8                         0  defaults
python                     2.7.9                         0  defaults
python                     2.7.9                         1  defaults
python                     2.7.10                        0  defaults
python                     2.7.10                        1  defaults
python                     2.7.10                        3  defaults
python                     2.7.10                        4  defaults
python                     2.7.10                        5  defaults
python                     2.7.11                        0  defaults
python                     2.7.11                        1  defaults
python                     2.7.11                        2  defaults
python                     2.7.11                        4  defaults
python                     2.7.11                        5  defaults
python                     2.7.12                        0  defaults
python                     2.7.13                        0  defaults
python                     2.7.13                        1  defaults
python                     2.7.13              h1b6d89f_16  defaults
python                     2.7.13              h9912b81_15  defaults
python                     2.7.13              hb034564_12  defaults
python                     2.7.14              h2765ee6_18  defaults
python                     2.7.14              h3e68818_15  defaults
python                     2.7.14              h4084c39_22  defaults
python                     2.7.14              h4a10d90_30  defaults
python                     2.7.14              h4a10d90_31  defaults
python                     2.7.14              h59f5a59_20  defaults
python                     2.7.14              h819644d_16  defaults
python                     2.7.14              h8c3f1cb_23  defaults
python                     3.3.0                         4  defaults
python                     3.3.1                         0  defaults
python                     3.3.2                         0  defaults
python                     3.3.3                         0  defaults
python                     3.3.4                         0  defaults
python                     3.3.5                         0  defaults
python                     3.3.5                         1  defaults
python                     3.3.5                         2  defaults
python                     3.4.0                         0  defaults
python                     3.4.1                         0  defaults
python                     3.4.1                         1  defaults
python                     3.4.1                         2  defaults
python                     3.4.2                         0  defaults
python                     3.4.2                         1  defaults
python                     3.4.3                         0  defaults
python                     3.4.3                         3  defaults
python                     3.4.3                         4  defaults
python                     3.4.3                         5  defaults
python                     3.4.4                         0  defaults
python                     3.4.4                         1  defaults
python                     3.4.4                         2  defaults
python                     3.4.4                         4  defaults
python                     3.4.4                         5  defaults
python                     3.4.5                         0  defaults
python                     3.5.0                         0  defaults
python                     3.5.0                         1  defaults
python                     3.5.0                         2  defaults
python                     3.5.0                         3  defaults
python                     3.5.0                         4  defaults
python                     3.5.1                         0  defaults
python                     3.5.1                         1  defaults
python                     3.5.1                         2  defaults
python                     3.5.1                         4  defaults
python                     3.5.1                         5  defaults
python                     3.5.2                         0  defaults
python                     3.5.3                         0  defaults
python                     3.5.3                         2  defaults
python                     3.5.3                         3  defaults
python                     3.5.4                         0  defaults
python                     3.5.4               h1357f44_23  defaults
python                     3.5.4               hc495aa9_21  defaults
python                     3.5.4               hd3c4935_11  defaults
python                     3.5.4               hdec4e59_20  defaults
python                     3.5.4               hedc2606_15  defaults
python                     3.5.5                h0c2934d_0  defaults
python                     3.5.5                h0c2934d_1  defaults
python                     3.5.5                h0c2934d_2  defaults
python                     3.6.0                         0  defaults
python                     3.6.1                         0  defaults
python                     3.6.1                         2  defaults
python                     3.6.2                         0  defaults
python                     3.6.2               h09676a0_15  defaults
python                     3.6.2               h6679aeb_11  defaults
python                     3.6.3                h210ce5f_2  defaults
python                     3.6.3                h3389d20_0  defaults
python                     3.6.3                h3b118a2_4  defaults
python                     3.6.3                h9e2ca53_1  defaults
python                     3.6.4                h0c2934d_2  defaults
python                     3.6.4                h0c2934d_3  defaults
python                     3.6.4                h6538335_0  defaults
python                     3.6.4                h6538335_1  defaults
python                     3.6.5                h0c2934d_0  defaults

C:\Users\Administrator>
```

