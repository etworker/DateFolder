# DateFolder
Organize photos and videos by recording date

按拍摄日期整理照片及视频

## 动机

作为某星座严重患者，完全无法忍受苹果手机照片拷到电脑上后一团糟的情况。
为此写了个小工具将照片按照拍摄日期来放置到各自的目录中。

## 使用教程

以我的iPhone 6s手机为例，将手机连接电脑，把DCIM目录复制到D盘根目录，这样就将手机中的全部图片和视频都保存到本地电脑了，如下图。

![](Doc\PhoneDir.jpg)

将`Bin\DateFolder.exe`下载至本地电脑，运行之，参考下面图片填入相关信息，点击处理按钮即可。

`相机名称`是为了将照片存入该名称下的目录。

`新建子目录`是为了让用户可以将某些图片手动放入该目录。
举例我是Instagram的重度用户，不希望将其和拍摄的原片混在一起，所以填入Instagram即可创建一个空目录。
如果希望创建多个子目录，只需用逗号分隔，如`Instagram,Favorite`。

`临时目录`是照片最终会去向何方。

![](Doc\AppUI.jpg)

处理结束后，临时目录下的文件结构如下：

![](Doc\FinalDir.jpg)

下一步就是根据每个日期的照片内容，修改日期文件夹的名称，如改为`2017_07_08 无聊乱拍`。

因为手机照片已经保存到了电脑，此时可以将其从手机上删掉以节省空间了。