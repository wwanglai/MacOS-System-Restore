# MacOS系统U盘安装盘安装系统的方法
## 参考网站
  * [如何为macOS创建可启动安装程序](https://support.apple.com/en-us/HT201372) - 苹果官方的制作U盘安装盘的方法
  
## 安装前的准备
  * 在Apple官方网站下载最新稳定版系统或是测试版系统，或是在系统偏好的Software Update中查看更新并且下载最新的系统。
  * 若是在Software Update中下载的最新系统，当macOS安装程序打开时，退出它而不继续安装。
  * 在Applications文件夹中找到这个安装程序，例如Install macOS Catalina Beta.app。[(在下面的命令行中对需要安装的系统名字进行替换)](#打开系统终端(Terminal),进行下面的命令操作)
## 备份
  * U盘和Mac上的所有需要的内容。（备份见XXX）
## 制作可用于安装的U盘（抹掉数据并设置为日志格式）
  1. 在MacOS操作系统中打开磁盘管理工具(Disk Utility)
  2. 选择需要用于制作的U盘，点击菜单栏的按钮Erase(格式化)
  3. 在弹出的窗口中（最好）将U盘名字更改为需要安装的系统的名字，然后选择Format为Mac OS Extended (Journaled).[(在下面的命令行中对需要安装的系统名字进行替换)](#打开系统终端(Terminal),进行下面的命令操作)
  4. 点击Erase进行抹除并格式化。
## 打开系统终端(Terminal),进行下面的命令操作
  * 将命令大括弧内的命令复制到终端下，并按回车进行制作【sudo **/Applications/Install\ macOS\ Catalina\ Beta.app**/Contents/Resources/createinstallmedia --volume /Volumes/***MyVolumes***
】
    * 说明1：大括弧中的加粗地址即为安装软件的地址，只需在操作界面进入Applications文件夹右键Copy文件并打开Terminal对粗体部分进行替换即可。
    * 说明2：大括弧内的斜体部分MyVolumes即为格式化时U盘的名字，同样对斜体部分进行替换即可。
## 完成安装盘制作以后，最好立即进行安装，在安装时，记得抹除Mac的数据，然后再进入新系统的安装。
 * 方法：重新启动，并长按option键。
  * 另一种方法：打开setup disk preference 将u盘设置为启动盘。
## 如果在安装系统或升级系统的过程中断网死机（紧急状况处理）
 * 可以尝试重启
 * 重启也无效的情况下
   * 关机
   * 插入安装盘（或者直接进行下一步，使用默认系统重安装系统）
   * command+option+R长按，并按下开机键
   * 进入网络系统恢复程序
   * 加载完成后选择reinstall MacOS，不会将数据和设置抹除，但可以重新安装系统。
