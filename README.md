# xxcmd
常用命令合集
# git 命令
    git add . (把当前文件夹下面的所有文件都添加进来)
    git commit -m "提交信息" (注:提交信息换成，自己的提交信息)
    git push -u origin master (注：此操作是把本地仓库push到github上面，这个步骤需要输入账号和密码)
    git status (查看当前的文件夹下文件的状态)
    git push origin master (发布master 分支)
    git branch -all (查看分支)
    git branch develop 创建develop分支
    git checkout develop 切换到develop分支
    git fetch （从远程仓库拉取所有分支信息到本地)
    git rebase origin/develop(将拉取的orgin/develop的内容合并到本地当前分支)
    git push origin feature/2将此分支提交到远程仓库，如果已经提交过，在保证你的版本库最新的情况下执行git push origin feature/2 –f
    git rebase –continue 冲突解决后执行

# 创建自己的命令行工具
|插件|安装方法|描述|
|----|-----|-----|
|commander|npm install commander|一个帮助快速开发nodejs命令行工具的package|
|chalk|npm install chalk| 终端输入时延时央视输出工具|
|gulp|npm install gulp|一个自动化构建工具,开发者可以使用它在项目开发过程中自动执行常见任务|
# 脚本解释程序:
```c
   #!/usr/bin/env node

   // 在程序的开头第一行，必须指定我们的脚本执行所需要的解释程序。
   // 在这里我门用node来做脚本解释程序。
   // env 用来找到我们的node, 并用node 来做程序的解释程序
```