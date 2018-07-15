# git学习

## 命令剪辑

- cd 文件路径;可以打开新的文件
- pwd 可以显示当前文件的路径
- mkdir 新建一个文件夹
- git init 初始化新建的文件



- git add 文本文件
- git commit -m “显示提交内容”。可以一次提交多个文件。
- git status 显示文本文件的状态
- git diff显示和上次的文本文件的区别
- git log修改日志
- git log --pretty=oneline简化显示日志



- git reset --hard HEAD^表示回退一位，HEAD~100.
- git reflog可以查看修改后的，使得修改再次找回git reset --hard 字符串
- ![![git-repo](https://cdn.liaoxuefeng.com/cdn/files/attachments/001384907702917346729e9afbf4127b6dfbae9207af016000/0)
- ]()
- git checkout --file 可以撤销最近的一次改动。
- ![1531460816375](C:\Users\ANOTHE~1\AppData\Local\Temp\1531460816375.png)
- git remote add origin git@github.com:AnoDAY/learngit.git
  git push -u origin master
- 、`master`才是指向提交的，所以，`HEAD`指向的就是当前分支。
- ![1531473618875](C:\Users\ANOTHE~1\AppData\Local\Temp\1531473618875.png)

![1531474361429](C:\Users\ANOTHE~1\AppData\Local\Temp\1531474361429.png)



- 当手头工作没有完成时，先把工作现场`git stash`一下，然后去修复bug，修复后，再`git stash pop`，回到工作现场。
- ![1531581993298](C:\Users\ANOTHE~1\AppData\Local\Temp\1531581993298.png)

![1531582932485](C:\Users\ANOTHE~1\AppData\Local\Temp\1531582932485.png)

- ```
   git config --global alias.st status
  ```

