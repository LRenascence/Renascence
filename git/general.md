https://www.jianshu.com/p/5e1820cfeebf

2.1远程库-->本地库
$ git clone git@github.com:LiShenglin111/Darling.git

（git clone:从远程克隆一份到本地

git@github.com:LiShenglin111/Darling.git    :我的SSH）

以后获取用  git pull origin master 



2.2本地库-->远程库
2.2.1本地库关联远程库：
$ git remote add origin git@github.com:LiShenglin111/Darling.git

2.2.2推送master分支的所有内容
（1）本地创建文本test.txt

（2）输入：$ git add text.txt

（3）输入：$ git commit -m"添加新文件"

（4）输入：$ git push -u origin master

第一次使用加上了-u参数，是推送内容并关联分支。

推送成功后就可以看到远程和本地的内容一模一样，下次只要本地作了提交，就可以通过命令：

$ git push origin master

把最新内容推送到Github
