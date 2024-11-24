先git checkout -b 新分支名字
就创建分支了，然后正常提交上去
提交完后仓库上就多出来一个分支，进入pr中新建分支然后提交即可
其中要记得点击合并分支
即base选主分支，compare选要合并的分支
一般是先从别人仓库fork过来，fork成自己的仓库，然后
git remote add upstream 地址
把原来的提交到上游
如果版本冲突，要git fetch upstream 从上游最新
然后git merge upstream/主分支
如此就更新完了