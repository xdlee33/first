# github教程

## 假设使用场景

写论文，修改论文，需要保存、方便查看、及时倒退到任何一个修改版本

## 0 登录

### 用户名

xdlee33

### 密码

19960716lxd

### 1 创建一个github项目（最好私有）

![image-20211215225121308](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215225121308.png)



![image-20211215225200078](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215225200078.png)

## 2 把刚才创建的项目下载到本地

### 2.1 打开git bash

![image-20211215225321805](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215225321805.png)

![image-20211215225356814](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215225356814.png)

### 2.2 进入github文件夹

#### 第1条指令作用：使git bash进入d盘

```bash
cd d:
```

#### 第2条指令：使git bash进入d盘下的github文件夹

```bash
cd github
```

此处也可以使用`ls`命令查看当前git bash的工作空间有哪些文件

```bash
ls
```

![image-20211215225740172](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215225740172.png)

#### 把创建的github项目下载到 D:\github

##### 去github获取下载链接

![image-20211215230014832](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215230014832.png)

##### 使用该链接在git bash中下载

```bash
# 注意，git clone后面跟的链接，不同项目，链接不同
git clone  git@github.com:xdlee33/papername.git

```

![image-20211215230307868](C:\Users\李旭东\AppData\Roaming\Typora\typora-user-images\image-20211215230307868.png)

### 第3条指令作用：使git bash进入d盘