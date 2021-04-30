cd MyGit:打开进入文件夹
mkdir myBlogSystem 创建文件夹
 git push -u origin master本地库的所有内容推送到远程库上。
git pull --rebase origin master 拉取远程仓库到本地库
git remote add origin git@github.com:    添加一个远程仓库
git remote -v查看远程列表
git commit -m "xxx"   提交到了 HEAD，但是还没到你的远端仓库。
git push origin master将这些改动提交到远端仓库
