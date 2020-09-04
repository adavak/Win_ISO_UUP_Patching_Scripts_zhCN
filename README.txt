支持 Windows 版本：

17763 - 正式发行版本
18363 - 正式发行版本
19041 - 正式发行版本
19042 - 测试版本
20xxx - 开发版本


运行 aria2_download_windows.cmd 开始下载最新补丁并开始制作集成补丁的 ISO。下载补丁文件地址为微软官方。

一些设置（位于文件夹根目录 ConvertConfig.ini）

NetFx3 = 1（若不想集成 .net 3.5，请改成0）
wim2esd =1（若不想生成 install.esd 减少空间占用。耗费大量的时间和计算机资源，镜像尺寸缩小25%左右，请改成0）

Supported Windows Version:

17763 - Release Version
18363 - Release Version
19041 - Release Version
19042 - Beta Version
20xxx - Dev Version

Run aria2_download_windows.cmd to start downloading the latest patches and start making ISO that integrate patches. The download patch files is from Microsoft official.

Some settings (located in the folder root ConvertConfig.ini)

NetFx3 = 1 (if you do not want to integrate .net 3.5, please change to 0)
wim2esd = 1 (If you don't want to generate install.esd to reduce space consumption. It takes a lot of time and computer resources, the image size is reduced by about 25%, please change to 0)

Tools:
7-zip (7-zip.org)
wimlib (wimlib.net)
aria2 (github.com/aria2/aria2)
oscdimg (Microsoft)

files folks from uupdump.ml
