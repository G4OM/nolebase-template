[Git安装链接](https://git-scm.cn/install/windows)<br>
[Git官方参考文档](https://git-scm.cn/docs)
-- -
Git是一个免费开源的分布式版本控制系统。
# 首次运行Git前的配置
# 获取、更新Git仓库
# 查看提交历史
# 撤销操作
# 远程仓库
# Git标签
# Git分支
# 服务器部署Git
# github
# 分布式Git

# 其他
- 配置用户姓名和邮箱：
>$ `git config --global user.name "Your Name Comes Here"`<br>
>$`git config --global users.email you@yourdomain.example.com`

- 创建一个名为`experimental(示例)`的新分支使用：<br>
>$ `git branch experimental(示例)`

- 查看现有分支的列表，输出结果带`*`标记是当前所在分支：
>$`git branch`

- 切换分支：
>$`git switch experimental(示例)`

- 提交更改： 
>$`git commit -a`

- 分支合并至master
>$`git merge experimental(示例)`


- 从头创建一个新仓库
> $ `mkdir project`<br>
> $ `cd project`<br>
> $ `git init`

- 将仓库克隆到新目录


