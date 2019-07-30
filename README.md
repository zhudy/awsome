# awsome
黑猴子的家：GitHub 之 gh-pages 新手入门:   https://www.jianshu.com/p/a2b647f4c999
黑猴子的家：GitHub 之 gh-pages:  https://www.jianshu.com/p/470ad39eac04

没那么复杂，直接在github页面Code下面创建一个"gh-pages" branch, 查看https://github.com/zhudy/awsome/settings 的Github Pages, 提示 Your site is published at https://zhudy.github.io/awsome/

本地更新后push到github：
$ git pull 
$ vi README.me
$ git add README.me
$ git commit ...	//commit to master
$ git push origin master //更新到tree master
$ git checkout -b gh-pages
$ git push origin gh-pages //更新到tree gh-pages
//访问https://zhudy.github.io/awsome/ 可以看到更新
