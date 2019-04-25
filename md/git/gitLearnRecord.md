###### 本地关联远程分支注意点

* 将本地分支与远程分支建立连接的方法

```
git branch --set-upstream-to=origin/master master  
```

* 遇见的坑

  [本地分支与远程分支](https://blog.csdn.net/u012145252/article/details/80628451)

  ```
  //不关联分支的 pull 操作 
  git pull origin master –allow-unrelated-histories
  
  //不关联分支的 push 操作
  $ git push <远程主机名> <本地分支名>:<远程分支名>
  也就是
  $git push origin master:master
  提交成功。
  ```

  



###### **idea 使用git**

注意 version control ssh executable 应设置为 **native**



