#介绍
bhxd - Bilibili History XML Downloader<br>
b站历史弹幕下载器

#运行环境
Linux各种发行版 Android5.1以上(配合Termux) Windows(配合Cygwin或其他类似软件)

#准备工作
1.安装w3m<br>
Centos/Fedora及其他RPM系Linux:<br>
(sudo) yum install w3m
<br>
Ubuntu/Debian/Android下的Termux等DEB系Linux:<br>
(sudo) apt-get install w3m
<br>
其他发行版在这不一一列举
<br>2.下载本程序 进入保存目录并授予可执行权限
<br>cd /THE/DIR/THAT/THIS/SCRIPT/SAVED
<br>chmod +x ./bhxd

#用法
bash ./bhxd [aid] [开始时间] [结束时间] [文件夹]
<br> 
支持的时间表示格式：
日期： "1926-08-17" 部分系统为"1926-08-17 CST"
Unix Timestamp：例如 @1471363200

#依赖
w3m cat
#License
版权没有 盗版不究

#更新日志
V1.1.0 增加进度显示、Ctrl+C停止、自动识别时间格式。
V1.2.0 增加输入信息正确性检测和延时确认。改善对Android With Termux的兼容性
