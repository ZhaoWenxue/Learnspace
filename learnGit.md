##### 第一次使用Git的时候，设置全局变量:
  git config --global user.name "your name"
  git config --global user.name "your email address"
##### git clone
  git clone 仓库地址
##### git push(提交三部曲)
  ###### 1.git add
    git add -A 或 git add .
  ###### 2.git commit
    git commit -m "本次提交修改的备注"
    （新创建的文件必须按照顺序提交，如果只是修改文件，也可用 git commit -am "本次提交修改的备注" 来合并前两步。）
  ###### 3.git push
    i.第1次提交到本分支
      git push origin master
      origin:远程仓库名  master:分支名（这里是主分支）
    ii.第2~n次提交到本分支
      git push
    iii.提交到其它分支
  ###### 4.git pull
    线上仓库和本地仓库不一致（协同开发）
##### 绑定本地仓库到GitHub
  ###### 1.git init 
  初始化本地文件夹为git仓库（生成一个.git的隐藏文件夹）
  ###### 2.git remote -v
  查看当前git仓库绑定的远程仓库
  ###### 3.git remote add origin 仓库地址
  绑定远程仓库
  
