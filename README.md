- [notebook](#notebook)
  - [windows](#windows)
    - [xshell自动更新位置](#xshell自动更新位置)
    - [docker初始化(不用，直接本地上虚拟机)](#docker初始化不用直接本地上虚拟机)
    - [锁频壁纸位置](#锁频壁纸位置)
    - [npm阿里镜像](#npm阿里镜像)
    - [IP查计算机名](#ip查计算机名)
    - [谷歌插件位置(注意刷新)](#谷歌插件位置注意刷新)
    - [谷歌接口调试model重置](#谷歌接口调试model重置)
    - [excel计算公式](#excel计算公式)
    - [ping各个网络](#ping各个网络)
    - [B7在E2到E240的出现次数](#b7在e2到e240的出现次数)
    - [bc Beyond Compare过期提示](#bc-beyond-compare过期提示)
    - [windows端口映射](#windows端口映射)
    - [建立软链接(/d建目录)](#建立软链接d建目录)
    - [win+R设置windows自动登录](#winr设置windows自动登录)
    - [双指触控修改 regedit](#双指触控修改-regedit)
    - [win+R 更改桌面图标](#winr-更改桌面图标)
    - [word自定义快捷键](#word自定义快捷键)
    - [开机自启配置 - win+R regidit](#开机自启配置---winr-regidit)
    - [WiFi管理](#wifi管理)
    - [windows清除默认打开方式](#windows清除默认打开方式)
    - [任务栏文件资源管理器起始位置](#任务栏文件资源管理器起始位置)
    - [IPV6路由表](#ipv6路由表)
    - [台电禁用HOME(Win键)：](#台电禁用homewin键)
    - [添加资源管理器到收藏夹](#添加资源管理器到收藏夹)
    - [睡眠启停(以管理员身份运行)](#睡眠启停以管理员身份运行)
    - [远程桌面记录 regidit](#远程桌面记录-regidit)
    - [win store充值](#win-store充值)
    - [刷新dns](#刷新dns)
    - [host文件](#host文件)
    - [fiddler拦截请求](#fiddler拦截请求)
    - [path备份](#path备份)
    - [outlook邮箱设置](#outlook邮箱设置)
    - [JDK1.8默认地址](#jdk18默认地址)
    - [文件夹别名](#文件夹别名)
    - [ditto快速粘贴搜索](#ditto快速粘贴搜索)
    - [bat添加到开始屏幕](#bat添加到开始屏幕)
    - [热键占用排查](#热键占用排查)
    - [google](#google)
      - [谷歌禁止自动更新](#谷歌禁止自动更新)
    - [qq邮箱关联outlook](#qq邮箱关联outlook)
    - [oracle](#oracle)
      - [sqlplus命令行操作](#sqlplus命令行操作)
    - [dos](#dos)
      - [windows文件列表到剪贴板](#windows文件列表到剪贴板)
      - [cmd字体](#cmd字体)
      - [内网路由表 dos](#内网路由表-dos)
      - [重置网络](#重置网络)
    - [eclipse](#eclipse)
      - [eclipse界面布局地址](#eclipse界面布局地址)
      - [eclipse安装lombook](#eclipse安装lombook)
      - [eclipse单独配置jdk](#eclipse单独配置jdk)
      - [eclipse反编译](#eclipse反编译)
      - [eclipse搜索非日志文件](#eclipse搜索非日志文件)
      - [eclipse常用快捷键](#eclipse常用快捷键)
      - [eclipse导入关联项目](#eclipse导入关联项目)
    - [idea](#idea)
      - [idea主动配置源（.xml/.classpath）](#idea主动配置源xmlclasspath)
      - [idea取消引号反引号自动配对](#idea取消引号反引号自动配对)
    - [svn](#svn)
      - [SVN账号密码修改地址](#svn账号密码修改地址)
      - [svn忽略文件](#svn忽略文件)
    - [tomcat](#tomcat)
      - [tomcat启动](#tomcat启动)
    - [office](#office)
      - [excel快速定位](#excel快速定位)
      - [excel自定义快捷键](#excel自定义快捷键)
      - [excel按列跨越合并](#excel按列跨越合并)
    - [github](#github)
      - [github请求地址](#github请求地址)

# notebook
## windows
### xshell自动更新位置
C:\Users\Administrator\AppData\Local\Temp\2\Patches<br/>
C:\Users\eshonulane\AppData\Local\Temp\Patches

### docker初始化(不用，直接本地上虚拟机)
docker-machine -s "D:\My_Hire\docker" create --engine-registry-mirror=https://bfq021f1.mirror.aliyuncs.com -d virtualbox default<br/>
docker-machine start/stop<br/>
docker-machine regenerate-certs default<br/>
docker-machine env default

### 锁频壁纸位置
C:\Users\eshonulane\AppData\Local\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\LocalState\Assets

### npm阿里镜像
npm install --registry=http://registry.npm.taobao.org<br/>
npm install node-sass --registry=http://registry.npm.taobao.org<br/>
npm config set registry https://registry.npm.taobao.org<br/>

### IP查计算机名
nbtstat -a 192.168.0.100

### 谷歌插件位置(注意刷新)
C:\Users\eshonulane\AppData\Local\Google\Chrome\User Data\Default\Extensions

### 谷歌接口调试model重置
```
moduleDiv = "<div class='panel panel-info no-radius b0 mt0 left-menu-border-top'>";	moduleDiv += "      <div class='panel-heading no-radius rel' data-parent='#modules'>";	moduleDiv += "          <div class='cursor collapsed' data-toggle='collapse' data-parent='#modules' href='#panel_ca_moduleId' crap-data='ca_moduleId' aria-expanded='false'>";	moduleDiv += "              <i class='iconfont module-title-ico f16'>&#xe624;</i>&nbsp;&nbsp;  ca_moduleName";	moduleDiv += "		        <span class='more'>";	moduleDiv += "			        <i class='iconfont fr h lh40'>&#xe75f;</i>";	moduleDiv += "			        <span class='t0 h'><i class='iconfont interface-menu rename-module mt0 lh40 fr'crap-data='ca_moduleId'>&#xe69e;</i></span>";	moduleDiv += "	                <span class='t0 h'><i class='iconfont interface-menu delete-module mt0 lh40 fr' crap-data='ca_moduleId'>&#xe69d;</i></span>";	moduleDiv += "			        <span class='t0 h'><i class='iconfont interface-menu down-module  mt0 lh40 fr' crap-data='ca_moduleId'>&#xe65e;</i></span>";	moduleDiv += "			        <span class='t0 h'><i class='iconfont interface-menu up-module  mt0 lh40 fr' crap-data='ca_moduleId'>&#xe8e9;</i></span>";	moduleDiv += "		        </span>";	moduleDiv += "          </div>";	moduleDiv += "      </div>";	moduleDiv += "      <div id='panel_ca_moduleId' class='panel-collapse BGEEE collapse' aria-expanded='false' style='height: 0px;'>";	moduleDiv += "          <div class='panel-body b0 p0'>";	moduleDiv += "              ca_interfaces";	moduleDiv += "           </div>";	moduleDiv += "       </div>";	moduleDiv += "   </div>";
```

### excel计算公式
需常规单元格

### ping各个网络
for /L %i IN (192,1,254) DO ping -w 2 -n 1 192.168.0.%i<br/>
cls<br/>
arp -a

### B7在E2到E240的出现次数
=COUNTIF(E2:E240,B7)<br/>
=COUNTIF($F$3:$F$100,J59)<br/>
B\d*:B\d*<br/>
B3:B100

### bc Beyond Compare过期提示
C:\Users\eshonulane\AppData\Roaming\Scooter Software\Beyond Compare 4
删除BCSessions.xml外其他文件, BCSessions.xml 删除Flags属性

### windows端口映射
netsh interface portproxy add v4tov4 listenport=58953 listenaddress=127.0.0.1 connectaddress=192.168.99.100 connectport=22<br/>
netsh interface portproxy add v4tov4 listenport=27891 listenaddress=192.168.1.80 connectaddress=192.168.137.10 connectport=22<br/>
netsh interface portproxy delete v4tov4 listenport=8180 listenaddress=192.168.8.185<br/>
netsh interface portproxy show all

### 建立软链接(/d建目录)
mklink D:\Winternet\ShadowsocksR-4.7.0\pac.txt D:\Winternet\Shadowsocks2.5\pac.txt<br/>
mklink C:\Users\eshonulane\.m2\settings.xml D:\Develop\Install\Java\apache-maven-3.5.3\conf\settings.xml

### win+R设置windows自动登录
control userpasswords2

### 双指触控修改 regedit
2FingerTapAction

### win+R 更改桌面图标
rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0

### word自定义快捷键
ctrl + alt + num+ 开始自定义快捷键(单击位置设置)

### 开机自启配置 - win+R regidit
计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run

### WiFi管理
1. Win+X||命令提示符(管理员)
2. 总览 输入netsh wlan show profiles
3. 查看 输入netsh wlan show profile name= "..." key=clear
4. 删除 输入netsh wlan delete profile name= "..."

### windows清除默认打开方式
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\FileExts\.dff\OpenWithList<br/>
右侧窗口即显示出dff文件“打开方式”中的应用程序。之前我们是用记事本方式打开的dff文件，所以OpenWithList里有notepad方式，就是记事本方式

### 任务栏文件资源管理器起始位置
默认C:\Users\逸宣\AppData\Roaming\Microsoft\Windows\Libraries
win7 %windir%\explorer.exe<br/>
改为 explorer shell:MyComputerFolder

### IPV6路由表
netsh interface ipv6 add route fec0:0:0:ffff::/48 6 fe80::ad85:d1d6:cfa0:19d2%21

### 台电禁用HOME(Win键)：
1. 运行注册表编辑器，定位至：HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout;<br/>
注意：还有个很接近的Keyboard Layos，不要选错了。（平板机油如果找不到注册表编辑器，可以就在开始面页找一个像放大镜一样的搜索图标，X16HD应该是在右上角，在搜索栏里面输入”regedit“再点击注册表编辑器）
2. 在右侧窗口新建一个“二进制值”，命名为“Scancode Map”;
3. 给“Scancode Map”赋值，就是点右键选修改二进制数据，这个数值的字符串比较长，输入时需要仔细一些：“
00 00 00 00     00 00 00 00     03 00 00 00     00 00 5b e0     00 00 5c e0     00 00 00 00”。
4. 完成后退出注册表编辑器，重启计算机使修改生效。什么时候需要恢复Win键了，把上述二进制值整个删除，再重启即可还原Win键。

### 添加资源管理器到收藏夹
user||eshonulane||链接||右键新建快捷方式<br/>
位置: 如   ftp://114.55.1.177/

### 睡眠启停(以管理员身份运行)
关闭休眠功能：@powercfg -h off<br/>
重启休眠功能：@powercfg -h on

### 远程桌面记录 regidit
HKEY_CURRENT_USER\Software\Microsoft\Terminal ServerClient\Default

### win store充值
win+R wsreset

### 刷新dns
ipconfig /flushdns

### host文件
C:\Windows\System32\drivers\etc

### fiddler拦截请求
开始 bpu http://....<br/>
清理 bpu

### path备份
```
%SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPowerShell\v1.0\;%SYSTEMROOT%\System32\OpenSSH\;D:\Woffice\AOMEI Backupper;C:\Program Files (x86)\AOMEI Backupper;c:\Program Files (x86)\QuickTime\QTSystem\;D:\Develop\Install\Git\cmd;D:\Develop\Install\TortoiseGit\bin;D:\Develop\Install\TortoiseSVN\bin;%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;%MYSQL_HOME%\bin;%MAVEN_HOME%\bin;%CATALINA_HOME%\lib;%CATALINA_HOME%\bin;%JAVA_HOME%\lib;C:\Program Files\Microsoft VS Code\bin;C:\Program Files (x86)\OpenVPN\bin;D:\Develop\Install\nodejs;D:\Develop\Install\TortoiseSVN\bin;C:\Users\eshonulane\AppData\Roaming\npm;
```

### outlook邮箱设置
```
sunline.cn
mail.sunline.cn
mail.sunline.cn

ulane.wang
pop3.ulane.wang		
smtp.ulane.wang

outlook.com
pop-mail.outlook.com
smtp-mail.outlook.com
```

### JDK1.8默认地址
C:\ProgramData\Oracle\Java\javapath;

### 文件夹别名
目录下新增desktop.ini，对应文件夹更改图标后复原，ansi编码
```
[.ShellClassInfo]
LocalizedResourceName=
```

### ditto快速粘贴搜索
搜索栏：\q textflag

### bat添加到开始屏幕
发送快捷方式到桌面<br/>
将快捷方式放到C:\ProgramData\Microsoft\Windows\Start Menu\Programs<br/>
在开始菜单应用列表中找到，右键添加到开始屏幕

### 热键占用排查
```
openark.exe
```

### google
#### 谷歌禁止自动更新
```
***直接安装不自动更新版***

<!-- regedit
计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Policies
新建key Google  
  新建key Update
    新建dword32bit UpdateDefault
      值 0 -->
```

### qq邮箱关联outlook
```
username
password
pop-mail.outlook.com
995
开启ssl
```

### oracle
#### sqlplus命令行操作
```
安装包
https://www.oracle.com/database/technologies/instant-client/microsoft-windows-32-downloads.html
instantclient-basic-nt-19.9.0.0.0dbru.zip
instantclient-sqlplus-nt-19.9.0.0.0dbru.zip
解压
cd D:\Develop\Install\plsql\client\instantclient_19_9
cmd
./sqlplus /nolog
conn zhangsan/password@10.0.1.242:1521/orcl;
执行文件
SQL>@D:\Develop\Install\plsql\client\sqltest\test.sql
update注意commit;
编码
服务端查看
select userenv('language') from dual;
环境变量添加
NLS_LANG AMERICAN_AMERICA.ZHS16GBK

//sqlldr
sqlldr ulane/***@***:1521/helowinXDB control=test.ctl data=loader.txt
```

### dos
#### windows文件列表到剪贴板
```
dir d:\ /B | clip
//过大可存入到文件,先创建
tpye nul>list.txt
dir d:\ /B > d:\list.txt
```
#### cmd字体
chcp 65001<br/>
chcp 936  //默认

#### 内网路由表 dos
添加 route add 10.22.0.0 mask 255.255.0.0 192.168.1.1<br/>
永久 route add -p 10.22.0.0 mask 255.255.0.0 172.20.20.0 metric 3 if 4(优先级3 4号网卡)<br/>
删除 route delete 10.22.0.0

#### 重置网络
1. NETSH INT IP RESET 
2. NETSH WINHTTP RESET PROXY 
3. IPCONFIG /FLUSHDNS 

### eclipse
#### eclipse界面布局地址
D:\Develop\Install\eclipse_pristine\workspace\.metadata\.plugins\org.eclipse.e4.workbench<br/>
C:\Develop\Install\eclipse_mars2\workspace\.metadata\.plugins\org.eclipse.e4.workbench<br/>
open a terminal

#### eclipse安装lombook
java -jar ${path}\lombok.jar

#### eclipse单独配置jdk
```
-vm
D:\Develop\Install\Java\jdk1.8.0_131\bin
```


#### eclipse反编译
```
enhanced class decompiler 3.1.1
```

#### eclipse搜索非日志文件
```
!*.log
```

#### eclipse常用快捷键
```
ctrl + t 查看继承实现类或方法
ctrl + alt + h 查看方法在哪里被调用
ctrl + shift + g 查看方法在哪里被引用
```

#### eclipse导入关联项目
批量导入有时无法初始化为maven项目，删除重新单个导入，初始化为maven格式后会自动关联


### idea
#### idea主动配置源（.xml/.classpath）
mvn idea:module<br/>
或<br/>
open 直接打开项目根目录

#### idea取消引号反引号自动配对
editor || general || smartkeys || insert pair quote

### svn
#### SVN账号密码修改地址
C:\Users\eshonulane\AppData\Roaming\Subversion

#### svn忽略文件
```
properties -> New -> svn:global-ignores
//已更改的文件无法忽略

.classpath
.project
*.iml
*.log
*.log.*
.idea
.settings
.eclipsespace
logs
log
target
dubbocache
//单独配置，如target已提交空目录，目录下新增文件时，会显示
classes
dfwy-autobulidapi.jar
generated-sources
maven-archiver
maven-status
test-classes
```
### tomcat
#### tomcat启动
```
环境变量直接设置,或者启动时set
SET JAVA_HOME=(JDK目录)
SET CATALINA_HOME=(解压后Tomcat的目录)
```

### office
#### excel快速定位
```
左上角名称框
F5 直接定位
```

#### excel自定义快捷键
```
选项 || 快速访问工具栏 || 所有命令...
alt按一次 + 4、5、6...执行
```

#### excel按列跨越合并
```
复制区域 || 粘贴到空白文档 || ctrl按一次 || t按一次（转置）|| 按行跨越合并 || 重复复制粘贴转置
粘贴时如果无转置选项，需要复制的源选项框包含一个已合并单元格（源选项框太简单，不会有太多粘贴选项）
若有边框注意合并后会缺失
```
### github
#### github请求地址
```
//只有pull可以，push只能https
https://github.com/...改为
git://github.com/...

//push问题
pac
github.com
github.global.ssl.fastly.net
//sourcetree代理
127.0.0.1
1080
向git配置文件添加代理信息
```
