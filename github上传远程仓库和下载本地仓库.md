#### 1. 配置查询
``` 
git --version   //查看git的版本信息
git config  // 配置指令
git config --system --list // 查看系统config
// 查看当前用户（global）配置
git config --global  --list
// 查看当前仓库配置信息
git config --local  --list
```
#### 2. 本地代码上传到github

1. 建立git仓库
 
   `git init`
 
2. 将项目的所有文件添加到仓库中
 
   `git add . // .可替换成特定的文件名，可指定特定文件添加`
 
3. 将add的文件commit到仓库中
 
   `git commit -m '注释语句'`
 
4. 本地仓库关联到github上的远程仓库
 
   `git remote add origin https://github.com/xxxx/xxxx`
 
5. 上传之前，先pull，
 
   `git pull origin master`
 
6. push戴拿到github远程仓库
 
   `git push -u origin master`
