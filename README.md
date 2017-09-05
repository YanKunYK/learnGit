# git使用教程
- 生成ssh-key
- 在github或者coding上面添加仓库
- 把生成的ssh-key公钥添加到github或者coding上
- git命令的学习和使用
- 备注：mac电脑安装了Xcode已经安装了git环境

### 生成ssh-key
- 1.用`git config`配置Git的user name和email
打开终端执行命令：`git config --global user.name "yourname"`
再执行命令配置邮箱： `git config --global user.email "youremail"`
- 2.生成SSH
a.查看是否已经有SSH密钥了：`cd ~/.ssh`用此命令进入后ls查看，如果有则备份删除。(或者直接删除)，另一种方法查看电脑之前是否存在SSH，同时按住shift+command+G 输入 ~/.ssh 
b.生成命令 `ssh-keygen -t rsa -C "youremai"`
然后按三个回车，密码设置为空，同时按住shift+command+G 输入 ~/.ssh  会发现生成了三个文件分别为 id_rsa 和id_rsa.pub和known_hosts三个文件
c.需要用的公钥就是在id_rsa.pub文件里了（用文本编辑打开）

###在github或者coding上面添加你的公钥和创建新的仓库

![](https://github.com/YanKunYK/learnGit/blob/master/pic1.jpg)
![](https://github.com/YanKunYK/learnGit/blob/master/pic2.jpg)
![](https://github.com/YanKunYK/learnGit/blob/master/pic3.jpg)
![](https://github.com/YanKunYK/learnGit/blob/master/img1.jpg)
![](https://github.com/YanKunYK/learnGit/blob/master/img2.jpg)
