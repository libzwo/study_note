# git

-  git init 

  > 初始化一个git仓库

- git add

  >git add [filename.suffix] 将文件添加到git仓库

- git commit

  >git commit -m "explain" 将文件提交到git仓库

- git status

  >查看仓库当前状态

- git diff

  >git diff [filename.suffix] 查看文件具体修改了什么内容

- git log

  >git log (--pretty=oneline) 加参数的话一行输出更加简洁明了

- git reset --hard [HEAD^]

  >HEAD代表当前版本，几个^就是退回几个版本,退回n个版本则用HEAD～n
  >
  >git reset --hard [版本号(可以就写前几个字母)]，回到那个版本

- git reflog

  >记录每一次命令，能查看历史记录方便回退版本

- git checkout -- [fileneame.suffix]

  >如果文件在工作区，则撤销工作区部分的修改，如果文件在暂存区，则撤销到了暂存区部分之后的修改

- git reset HEAD [filename.suffix]

  > HEAD表示最新的版本，几个^表示回退几个版本

- git rm [filename.suffix]

  >用rm删除文件后，还要从版本库中删除文件git commit

- git branch

  >查看当前分支

- git branch [name]

  > 创建名为[name]的分支

- git checkout [name]

  > 切换分支

- git switch [name]

  > 切换分支（同上）

- git checkout -b [name]

  > 创建并切换分支

- git swtich -c [name]

  > 创建并切换分支（同上）

- git branch -d [name]

  > 删除分支

- git push origin master

  > 本地提交后推送最新修改到gitthub
