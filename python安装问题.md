1.安装scoop出错，提示无法连接到远程服务器，折腾了一天没搞定。最好怀疑是代理的问题。
2.换了代理服务器，安装scoop搞定。
3.第二步，安装git不成功
4.通过运行scoop checkup，发现有很多warring和error，按照提示（需要运行系统给出的一些命令）
5.这些命令主要是安装7zip，innounp。运行scoop list，如果后面不提示failed，就表示成功了。
6.上面有几次反复，反复install，uninstall，最后成功了。
7.接着安装git，就没什么问题了。
8.运行scoop update，出问题，经过从网上找帮助，下边这个方法搞定：
C:\Windows\System32\drivers\null.sys 这个文件损坏,下载好了null.sys文件，切记先删除原有的null.sys，再把新的
null.sys文件复制到进去，（不能直接覆盖原文件！！不能直接覆盖原文件！！不
能直接覆盖原文件！！）然后重启电脑。(null.sys文件在本文件夹下）
9.下面安装python就没什么问题了，一路顺风。
10.安装 Visual Studio Code顺利
