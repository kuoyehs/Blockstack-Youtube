# Blockstack-Youtube
-------------------
## HW6: 根据 demo 的 feature-radiks-userGroup 分支完成自己的产品技术流程图设计，并提交在自己开发的产品仓库中，将产品仓库链接提交到下方

![image](https://github.com/kuoyehs/Blockstack-Youtube/blob/master/readme_img/5.png)

视频分为公开，特定公开，与不公开 3 种

1.公开：视频资讯（e.g.：视频title，duration，热门影片，首页，动态…...）可以由gaia明文来存取，一般人能看到视频资讯与播放视频
2.不公开：视频资讯可以由gaia密文来存取，只有自己能看到视频资讯与播放视频
3.特定公开：视频资讯可以由拥有者定向授权给特定用户观看，可以使用第六课的Radiks用户分组授权功能来存取

-------------------


## 思考去中心化产品，产品流程图,去中心化的Youtube：
-------------------
## HW3: 

### 那些data是公开：

视频本身相关data（e.g.：视频title，duration，热门影片，首页，动态…...），因为每个人都可以看视频

### 那些data是保密：

每个用户观看视频的详细资讯（e.g.:观看记录，收藏列表，播放列表，记录前次观看视频的时间...... ）

-------------------
##设计

![image](https://github.com/kuoyehs/Blockstack-Youtube/blob/master/readme_img/1.png)

![image](https://github.com/kuoyehs/Blockstack-Youtube/blob/master/readme_img/2.png)

![image](https://github.com/kuoyehs/Blockstack-Youtube/blob/master/readme_img/3.png)

![image](https://github.com/kuoyehs/Blockstack-Youtube/blob/master/readme_img/4.png)

本项目以 [Create React App](https://github.com/facebook/create-react-app) 为框架启动

### `npm install`
安装依赖包

### `npm start`
运行程序，在 localhost:3000 端口查看应用执行情

### 执行情况

![](resources/a.png)

- 登入后显示主界面
- “你好、个人简介”等文字在 Profile.js 中可以查看


![](resources/b.png)
- 打开检查
- AppConfig
- UserSession
- Person
- 对应代码查看相应内容
