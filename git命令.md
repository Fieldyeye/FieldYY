
# git命令
- 切换至master分支：git checkout master
- 获取最新更新  git pull origin master
- 扩展分支  git checkout -b branchname
  此命令将创建一个名为"branchname"的新分支并移动至其中
- 执行git检查  git status
- 准备下一步  git add
- 记录变更  git commit
- 发布变更  git push


配置git用户

- git config --global user.name  //user名

- git config --global user.email //mail

到项目工作空间目录

- git init  //初始化工作空间，在目录下生成.git文件

- git add "" //本地文件添加到缓存区

- git commit -m  "" //提交

- git status //查看git文件状态

- git log  //查看git提交记录

版本回退操作

- git reset --soft HEAD~1 or 版本号  // 回退本地仓库到版本号


- git reset --mixed HEAD~1 or 版本号 //回退本地仓库和暂存区到版本号

- git reset --hard HEAD~1 or 版本号 //回退本地仓库、暂存区和工作目录到版本号

版本比对

- git diff  //比较未被暂存的文件改动了哪些
- git diff --cache  //比较被暂存文件改动了哪些
- git diff --cache filename //比较被暂存的这个文件改动了哪些

修改最后一次提交


- git commit --amend  //进入vim窗口编辑
- git rm  //删除文件
- git mv  //重命名文件名


创建分支

- git brach name  //创建一个名为name的分支
- git checkout name //切换到名为name的分支
- git log --decorate --oneline //查看当前分支明细
