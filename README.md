# 创建基于github的毕设项目
# 请各位同学观看录像，并按照录像中的步骤在github上创建自己的毕设项目，最后将自己项目的项目的提交日志页面提交上来
## 操作录像
链接: https://pan.baidu.com/s/1umHrZVtgAkFtcIviGRPMDw 提取码: 8dbk
## 地址提交页面
【腾讯文档】_提交日志页面
https://docs.qq.com/sheet/DT0dqdGd3SFVPdHpJ?c=G3A0A0

## 存在的问题
1. windows下ssh-keygen 不是内部或外部命令和打开id_rsa.pub，该文件在git安装目录下的`usr/bin`中，需要将其加入到path中，具体操作步骤可以参照以下文章：
[windows下ssh-keygen 不是内部或外部命令和打开id_rsa.pub文件](https://blog.csdn.net/a419419/article/details/80021684)


1. 安装git

1.1 下载git

1.2 安装git

2. 注册github账号
```
qutgitstudent
zhouwei@qut.edu.cn
qtech1234!!
```

3. 创建github仓库(repository)

仓库名字以`姓名项目名`方式命名，使用驼峰拼写

4. 创建公钥私钥

4.1 配置git账户

4.2 创建密钥

4.3 将公钥`id_rsa.pub`中的内容在github中建立密钥

5. 将github上建立的项目clone到本地磁盘，比如e盘底下某个目录

这步执行有问题，可以多试几遍git clone命令，每次试之前要把上次clone的目录删掉

6. 以后可以执行同步脚本`syn.bat`

以后可以直接在本页面下载该文件到你的仓库即可，每次修改完仓库内容，可以点击执行该bat文件完成同步，也可以在IDE中进行同步，下面会介绍

7. IDEA中进行git操作

这是可以仍旧使用`syn.bat`进行同步，也可以通过IDEA进行操作，直接进行commit提交至本地仓库操作，然后使用push更新至github远程仓库。不是IDEA操作的文件，比如这里的本文文件就不会被IDEA更新至github，仍然需要使用`syn.bat`进行同步。大家可以把自己的毕设论文word文件放到这里，每次可以自动保存最新的版本。
再演示一次由IDEA进行更新操作。

8. 最后把建好的github项目的提交日志页面，如`https://github.com/qutgitstudent/ZhouWeiMyGithubProject/commits/master`汇报上来，用以老师进行检查。
