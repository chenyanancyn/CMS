# 1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
      new gist 创建新的代码
      new organization  创建新的组织
      new repository 创建新的仓库
      import respository 导入仓库

# 2.如何能将仓库中的html文件直接解析成页面？
      settings设置->github pages->sourse->master master->save 

# 3.如何删除仓库
      settings->delete

# 4.Bash是什么操作系统的命令
      linux

# 5.Pwd是什么命令
      print working directory  打印当前工作目录

# 6.Cd是什么命令
      change directory  改变目录

# 7.Echo是什么命令
      打印 

# 8.配置git用户名的命令
      git config --global user.name ""

# 9.配置邮箱的命令
      git config --global user.email ""

# 10.命令行换行方式
      \

# 11.命令行终结方式
      ctrl+c

# 12.使用命令行比GUI方式有何优势
      比GUI的效率高
      github提供的功能有限 
      github只能局限于创建文件、编辑几个文件，无法创建文件夹
      在github上不能对多个文件进行同时编辑

# 13.提交到本地仓库时为什么有暂存区
      workspace中可能会有好多编辑，可以将所有编辑同时提交到index中，而从index提交到repository时，可以将灵活的将编辑内容进行提交
      回撤时变动的影响是不同的，范围是不一样的
      在进行commit提交时，可以控制提交的颗粒度

# 14.新建代码仓库的命令
      git init

# 15.git clone [url] 这个命令的作用是
      下载一个项目和它的整个代码历史

# 16.添加指定文件到暂存区的命令
      git add [file1] [file2]

# 17.删除工作区文件，并且将这次删除放入暂存区的命令
      git rm [file1] [file2]

# 18.改名文件，并且将这个改名文件放入暂存区的命令
      git mv [file-origin] [file-rename]

# 19.提交暂存区到仓库的命令
      git commit -m [message]

# 20.直接从工作区提交到仓库的命令
      git commit  -a -m [message] #前提是该文件已经有仓库中的历史版本

# 21.显示变更信息的命令
      git status

# 22.查看历史信息的命令
      git log

# 23.Commit的意义是
      代码提交到仓库

# 24.Pull的意义是
      将远程仓库的提交拉下到本地

# 25.Push的意义是
      将本地的提交推送到远程仓库

# 26.cp   copy

