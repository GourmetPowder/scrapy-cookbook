# git迁移仓库地址（保留分支和历史提交）

* 先克隆老项目的镜像

`git clone --mirror old.git (old.git 为老项目的git地址)`

* 进入老项目的目录

`cd old.git`

* 移除老项目的地址替换成新项目

`git remote set-url --push origin  new.git (new.git 为新项目的git地址)`

* 将镜像推到远程

`git push --mirror  //这一步需要输入新的git的账号和密码`
