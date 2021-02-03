支持简体中文 Windows 版本：

19042 - 正式发行版本
20xxx - 开发版本

**与 www.uupdump.net 下载下来包的区别：** 
**增加了移除 flash 和更新 .net 补丁包。**

运行 aria2_download_windows.cmd 开始下载最新补丁并开始制作集成补丁的 ISO。下载补丁文件地址为微软官方。

一些设置（位于文件夹根目录 ConvertConfig.ini）

NetFx3 = 1（若不想集成 .net 3.5，请改成0）
wim2esd =1（若不想生成 install.esd 减少空间占用。耗费大量的时间和计算机资源，镜像尺寸缩小25%左右，请改成0）

Tools:
7-zip (7-zip.org)
wimlib (wimlib.net)
aria2 (github.com/aria2/aria2)
oscdimg (Microsoft)

files folks from www.uupdump.net
