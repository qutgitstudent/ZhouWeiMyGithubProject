# 创建基于github的毕设项目
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
