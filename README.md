# 创建基于github的毕设项目
1. 安装git
1.1 下载git
1.2 安装git
2. 注册github账号
3. 创建github仓库(repository)
仓库名字以`姓名项目名`方式命名，使用驼峰拼写
4. 创建公钥私钥
4.1 配置git账户
4.2 创建密钥
4.3 将公钥`id_rsa.pub`中的内容在github中建立密钥
5. 将github上建立的项目clone到本地磁盘，比如e盘底下某个目录
这步执行有问题，可以多试几遍git clone命令，每次试之前要把上次clone的目录删掉
6. 以后可以执行同步脚本`syn.bat'