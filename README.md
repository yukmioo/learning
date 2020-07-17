# learning
如何打开git cmd
  1. 打开git目录的文件夹，通过路径栏输入cmd，打开命令行界面
  2. 在这里可以创建学习过程中的记录的python文件，后缀为.py。 例如 abc.py
****  
如何将本地git代码上传到github上：
  1. 首先可以使用**git status**可以看到本地git仓状态。 例如：D:\GithubPlayGround\learning>git status
  2. 再用**git add** \<yourfile\>， 将untracked file变为跟踪中的文件。 例如：D:\GithubPlayGround\learning>git add abc.py<br />
    Note: 可以使用git status查看当前状态，如无意外的话，之前添加为跟踪的文件已经成了绿色的Changes to be committed:
  3. 使用**git commit**提交代码<br />
    Note: git commit后会出现填写提交说明的文件，使用 **a** 键编辑，使用 **Esc** 退出编辑再用 **:wq** 保存退出后即可
  4. **git push**
****
如何同步github仓库上的内容到本地电脑
  1. 在本地与GitHub仓没有冲突时，使用**git pull**即可完成
  2. 当本地仓库也有另外的修改同时需要下载GitHub上的修改时，可以先用git stash save xxx (xxx指自己写的标注)
  3. 当本地的修改想去掉的时候使用git checkout \<yourfile\>，可以将本地文件退回到GitHub仓库同步状态
