分支相关命令
 $ git branch dev    创建dev分支
 $ git checkout dev  切换dev分支

 $ git checkout -b dev 创建并切换dev分支

 合并分支主分支合并dev分支,首先要切换到master分支
 $ git merge dev
  实现分支合并时可能会进入编辑模式 输入 :wq 退出编辑模式