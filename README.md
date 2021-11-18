# GamesenseLuaCloudloader
**简介：**
它是一个简单且开源的lua云加载系统，它可以让您在没有编程能力或者懒得为此编写代码的情况下快速创建自己的lua云载入并且快捷地添加/删除/禁止用户。
它为开源项目，您可以轻松地添加自己的特性。

**安装：**
您需要：一台运行http MySQL服务的服务器 和10IQ。

1. 配置http MySQL环境(建议使用xampp)。
2. 将php文件上传到服务器，并且更改每个文件中的数据库信息。
3. 打开lua文件，将每个php接口的地址填入。
4. 使用phpmyadmin导入sql文件并且添加条目，详情请看说明文件。
5. 测试lua。
6. 出云载参数，走上人生巅峰。

**问题/bug：**
无法卸载已加载的lua。

**计划：**
添加卸载lua功能。
添加用户组标识。

**其他：**
QWQ?

演示:https://www.bilibili.com/video/BV1Dp4y147yG



**一些信息**:

我认为实际上通过ffi获取一些能代表hwid的数据是完全可能的，不过重点仍然在于如何加密通讯，http或者https都是不安全的，我不知道能不能通过ffi构建UDP通讯系统。

此项目已经停止更新(也不一定)。

