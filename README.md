# likui
小旋风
后端
准备环境
JDK1.8、IDEA、Maven、Mysql5.7+、Navicat

安装步骤
1、打开IDEA后，选择 “open” 打开 “volunteer-backend”” 项目

2、IDEA配置好 “JDK1.8” 和 “Maven”，刷新等待编译成功

3、使用Navicat导入数据库文件 db_volunteer.sql

4、在”application-dev.yml”中配置好数据库配置

5、在”application-dev.yml”中配置好图片路径

前端
准备环境
Node 16.13.2， 或者更高的版本（可能出现不兼容编译失败的情况）

安装步骤

1、打开 “volunteer-frontend” 目录

这里可以选择使用 “cmd”、”Vscode”、”WebStorm”、”IDEA” 等能够打开和编译vue环境即可



2、在”终端”执行命令：

npm config set registry https://registry.npmmirror.com

3、在”终端”执行命令：

npm install

*等待编译成功

4、在”终端”执行命令：

npm run dev
