注：增加一个修改记录，方便文档管理和跟团队其他人协作。用表格的形式，让人一目了然<br>
# 修改记录
> |版本|作者|版本描述|日期|说明|
> | -------- | ------- | :------- | :------- | :------- |
> | 1.0 | jinyi | 初稿 | 2019-07-25 | 安装MacBook Pro Catlinna Beta 的备忘录 | 
> | 1.0.1 | baba | 文档格式修改 | 2019-08-02 | 增加修改记录表格等 | 

# 系统安装及重装
   * 【说明】描述要简洁，不要很多句，这个文档的标题就是MacOS安装相关的，从文档就可以看出来了，因此，内容中不用重复，这样文档更简洁。。另：将相关的内容写在一个文档，通过章节来确定，任务的内容（就是这部分要作什么）。
   * 参考
     + [Get ready for macOS Mojave](https://support.apple.com/macos/mojave)<br>
     + [How to reinstall macOS](https://support.apple.com/en-ae/HT204904)<br>
  ## 安装
       + 安装前准备
  ## 重装
       + 重装前准备
# 系统环境设置
## 初始设置
   * Enable the root user
        + 参考
           - [Enable the root user in macOS Sierra](https://coolestguidesontheplanet.com/enable-root-user-macos-sierra/)<br>
        + Steps<br>
           1. As an admin user launch System Preferences from the Apple Menu.<br>
           2. go to the User and Groups pane.<br>
           3. authenticate first by clicking on the padlock icon down the bottom left.<br>
           4. then click on Login Options to see some options on the right.<br>
           5. Then click the Join… button next to Network Account Server.<br>
           6. This will pop up a dialog window, from here click on Open Directory Utility.<br>
           7. go to the Edit menu and select Enable root user, then finally set a password for the root user.<br>
# 应用安装
## 系统软件的安装（包括配置）
## 应用软件的安装（包括配置）

## 安装brew
 
 * [brew官方网站install](https://brew.sh)
 * [homebrew——GitHub下载](https://github.com/Homebrew/brew)
## 安装ruby
 * 通过brew下载安装
## 安装Xmind
 * 通过brew下载安装
## 安装git
 * brew install git

## 安装macport
 * [MacPort官网](https://www.macports.org/install.php)
   *  通过source进行install
   *  具体操作见官网。
   *  profile文件添加：
     * export PATH=$PATH:/opt/local/bin
     * export PATH=$PATH:/opt/local/sbin
 * 安装过程中如果有bug，参考文件：MACOS_XX-Net安装步骤.xmind
## 安装wget
 * brew install wget
## 安装python3
 * brew install python3
 * 将系统配置文件添加python3软链接
## 安装mysql
 * brew search mysql
 * brew install mysql
   * Warning: You are using macOS 10.15.
We do not provide support for this pre-release version.
## 安装mongoDB
 * 疑问：需要安装package还是formulae？
 * brew install mongoDB
   * Warning: You are using macOS 10.15.
We do not provide support for this pre-release version.
## 安装微软办公
 * 未激活
