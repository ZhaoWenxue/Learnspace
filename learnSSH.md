###### 生成本地SSH
  ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
###### 获取本地SSH
  cat ~/.ssh/id_rsa.pub
###### 第一次使用Git的时候，设置全局变量:
  git config --global user.name "your name"
  git config --global user.name "your email address"
###### git clone
  git clone 仓库地址
