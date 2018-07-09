# graduation project
这是一个毕业设计的内容2017年4月16日
----
## 一 、系统环境要求
+ 硬件要求：内存512M及以上为佳
+ 软件需求：
	+ 操作系统版本： windowXP及以上
	+ 浏览器：chrome或Firefox浏览器
	+ 后台环境：xampp软件集成的Apache服务器加上MySQL数据库
	+ 开发语言：HTML、CSS、JavaScript、PHP

## 二、系统使用
+ 1、本套系统依托于xampp的集成开发环境，因此第一步需要安装并且启动xampp，安装的时候需要记住自己的安装目录（后期的开发，建立文件夹，都是在这个根目录下的htdocs下完成的）。
+ 2、检查xampp的相关服务的端口是否被占用。在软件的netstat按钮出可以查看本电脑目前启用的所有端口，主要是需要Apache的80、443端口以及MySQL的3306端口。
+ 3、单击xampp上Apache和MySQL的start按钮，启动这两个服务，这样本地电脑即使客户端也是服务端。（注意：启动的时候需要观察相关的端口是否被占用，Apache使用80和443两个端口以及MySQL使用3306这个端口，如果有当中的端口被占用，可以尝试重启电脑或者关闭相关端口进程，如果还是被占用，需要修改相关配置文件）。
+ 4、开发的代码放置在xampp根目录下的htdocs这个文件夹里，Apache服务器可以直接访问这个文件，初次使用可能会有demo文件，可以直接删除。
+ 5、本地网页的打开模式：localhost:80在这个域名端口下，打开htdocs中的文件即可，这里需要，也可以在本地编辑器中直接配置浏览器访问的端口，可以达到一样的效果。
+ 6、以上步骤执行完毕并且没有问题后，我们可以在浏览器访问我们的文件了。可以查看动态网页了。
+ 7、项目使用：
	+（1）首页：出去整体的静态展示功能，还有一个留言板的添加、以及留言精选的展示功能，以上这两个都是会与后台数据库进行交互。
在个人中心我们以管理员账号（130102010153）登录，是可以筛选留言的。
	+（2）借阅管理：任何人都可以在任何情况下搜索图书（需要输入图书全名），然后只有登录的用户可以在展示的图书中租借图书（注：未登录者可以在个人中心当中登录）。租借图书会在展示图书下方形成一个书架，可以借阅和删除，只有当借阅被点击后才会在数据形成有效数据。
	+（3）个人中心：登录（管理员账号：130102010153，密码：123456789；普通用户：130102010145，密码：123456789），管理员可以重置用户密码（修改密码为学生学号），图书管理，留言管理，修改密码。普通用户可以查看信息，退出登录，修改密码，查看借阅记录。

