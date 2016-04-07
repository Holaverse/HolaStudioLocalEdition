#### HolaStudio 安装说明

#### windows 环境安装

+ 1、下载安装包  

  ![exe](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B78.PNG)

+ 2、双击安装  
双击安装包开始安装后会出现一个安装动画:  
![install](http://7xsec6.com1.z0.glb.clouddn.com/install.png)

+ 3、等待安装完毕后会在桌面创建一个快捷方式：
![shortcut](http://7xsec6.com1.z0.glb.clouddn.com/146002426550555.png)

+ 4、双击即可启动HolaStudio  
![demo](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B72.PNG), ``简洁大方的界面设计``

+ 5、数据路径  
默认数据路径：![path](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B74.PNG)

`app-3.4.1`根据不同版本号目录名称略有不同。

**修改数据路径：**

为了便于协作开发可以把游戏所在的目录更换到自定义目录：
![dir](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B75.PNG)

**游戏路径生成规则：**  
每个游戏都在对应的组织下，文件路径按照`组织ID`以及`游戏Key`来生成：  
![dir](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B76.PNG)

*需要协作的用户可以把该目录建成一个`git`仓库，达到协作的目的。*

---  

#### Mac OSX 环境安装

+ 1、下载安装包
![mac-install](http://7xsec6.com1.z0.glb.clouddn.com/mdg.png)

+ 2、安装  
![mac_install](http://7xsec6.com1.z0.glb.clouddn.com/146002682487912.png)

+ 3、启动HolaStudio  
![startup](http://7xsec6.com1.z0.glb.clouddn.com/start.png)

+ 4、数据路径  
默认数据路径：![path](http://7xsec6.com1.z0.glb.clouddn.com/path.png)

**修改数据路径：**

为了便于协作开发可以把游戏所在的目录更换到自定义目录：
![dir](http://7xsec6.com1.z0.glb.clouddn.com/%E6%8D%95%E8%8E%B75.PNG)

**游戏路径生成规则：**  
每个游戏都在对应的组织下，文件路径按照`组织ID`以及`游戏Key`来生成：
![dir](http://7xsec6.com1.z0.glb.clouddn.com/ins.png)


*需要协作的用户可以把该目录建成一个`git`仓库，达到协作的目的。*

---

#### 关于游戏目录结构的几点说明  
- 1、带前后下划线的文件以及文件夹为Studio需要的配置文件，**请勿删除或改动**  
- 2、第三方库文件放置在游戏目录下的`libs`文件夹下  
- 3、修改数据目录必须确保目录已经存在  
- 4、修改数据目录成功后，原目录下资源不会被删除，请自行删除  
