## 							git和github学习笔记

# 1.常见

*  ## watch

如果watch到了某个项目，以后只要这个项目有任何更新，都会第一时间收到关于这个项目的通知提醒。

* ## fork

1.如果遇到了某个喜欢的项目，而已将仓库直接复制到自己仓库下面。

2.也可以用pull request 将原代码进行改进之后合并到原有项目里。

* ## star

1.可以将某个喜欢的项目收藏。

* ## issue

发现代码BUG，但没有成型代码，需要讨论时用。

# 2.仓库管理

* ## 创建文件

![image-20200301165658484](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301165658484.png)

创建一个新的文件，可以在里面书写格式

![image-20200301165825007](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301165825007.png)



最后提交即可![image-20200301165838287](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301165838287.png)

* ## 删除文件

![image-20200301171215158](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301171215158.png)

点击右边垃圾桶就可以删除

删除之后可以在commit查看

![image-20200301171242042](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301171242042.png)

![image-20200301171253551](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301171253551.png)

* ## 上传文件

![image-20200301171410542](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301171410542.png)

![image-20200301171424431](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301171424431.png)

* ## issue

![image-20200301172240516](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301172240516.png)

* 个人主页

![image-20200301173734879](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301173734879.png)

* 开源贡献流程

1）新建issue

提交使用问题或者建议

2）Pull Request

1.fork项目

2.修改自己仓库的项目代码

3.发起pull request

4.等待做着操作（审核）

* # 3.git

## 用git提交



![image-20200301200505766](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301200505766.png)

* 基本信息配置

![image-20200301201547173](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-

![image-20200301201801682](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301201801682.png)

  git config --global user.name "Your Name"

  git config --global user.email "you@example.com"

* 在文件内初始化git（创建git仓库）

git init

(创建文件 touch + 文件名)

![image-20200301202003662](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301202003662.png)

* 提交
* ![image-20200301203252995](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301203252995.png)
* 

![image-20200301202141834](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200301202141834.png)

* # github远程仓库

1,将本地仓库同步到git远程仓库中

<img src="C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200302095534101.png" alt="image-20200302095534101" style="zoom:%;" />

# git克隆操作

目的

将远程仓库（github对应项目）复制到本地

## 代码

``` git
git clone “仓库地址”
```

将本地仓库同步到git远程仓库中

``` git
git push
```





* # 无权限怎么办

![image-20200302101603444](C:\Users\39201\AppData\Roaming\Typora\typora-user-images\image-20200302101603444.png)

