# netmusic-app
欢迎star issue

[English](README.zh.md)

仿网易云音乐APP的微信小程序

[还有Vue版本哦](https://github.com/sqaiyan/neteasemusic)

需后端支持
下载启动[node服务端](https://github.com/sqaiyan/netmusic-node)即可


### 项目结构 <!-- by 赵宇 -->

```
NeteaseMusicWxMiniApp
├── image/               # 静态资源
├── page/
│   ├── component/       # 页面组件
│       ├── album/
│       ├── artist/
│       ├── cloud/
│       ├── djradio/
│       ├── fm/
│       ├── home/
│       ├── login/
│       ├── me/
│       ├── mv/
│       ├── new/
│       ├── playing/
│       ├── playlist/
│       ├── program/
│       ├── recommend/
│       ├── record/
│       ├── recsongs/
│       ├── search/
│       ├── simi/
│       ├── toplist/
│       ├── user/
├── screenshot/          # 截图
├── utils/               # 函数模块
├── app.js               # 主入口
├── app.json             
├── app.wxss             
├── LICENSE
├── README.md
```


### 主要功能截图 <!-- by 赵宇 -->

### home

![页面截图](screenshot/home.png)

应用主页面，主要功能为首页推荐，歌单列表，电台，播放控制


### login

![页面截图](screenshot/login.png)

应用的登录逻辑,实现了简单的用户登录功能
* onLoad:初始化传入的数据
* textinput:监听用户输入
* wx.request:登录验证



### me

![页面截图](screenshot/me.png)

用户播放列表管理功能，包括获取用户的订阅统计和播放列表数据




### mv

![页面截图](screenshot/mv.png)

应用的MV模块，实现视频详情页面，包括获取视频信息、切换标签页显示不同内容以及加载更多评论的功能
* tab 处理标签页切换加载
* common.loadrec 调用该方法获取更多评论数据


### new

![页面截图](screenshot/new.jpg)

实现音乐排行榜页面，包括获取不同国家的歌曲和专辑排行榜数据、切换标签页显示不同内容以及加载更多内容的功能
* 在data中定义了变量来存储不同国家的歌曲和专辑排行榜
* tabtype用于处理标签页切换操作并加载相应国家的排行榜数据
* getsongs 和 getalbums 函数分别用于获取歌曲和专辑的排行榜数据，并根据国家和地区进行分类



### 目前实现功能

1. 用户
2. 歌单
3. FM
4. 播放
5. 评论
6. MV
7. 专辑
8. 歌手
9. 登录
10. 歌曲红心,FM trash，收藏单曲至歌单
11. 收听记录
12. 歌单歌曲推荐
13. 迷你播放条
14. 电台，节目
15. 搜索









### TODO

* 增加评论，评论点赞等 
* 歌词翻译
* 收藏(歌单，歌手，专辑，电台)
* 音质切换
* 用户动态，粉丝
* 新歌 新专 分类电台
 
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4271.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4279.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4274.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4272.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4276.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4277.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4275.PNG"/>
<image width="340" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/IMG_4273.PNG"/>

### 如果本示例对您学习小程序有帮助欢迎大佬赏杯奶茶喝
<image width="220" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/wx.jpg"/><image width="220" src="https://github.com/sqaiyan/NeteaseMusicWxMiniApp/raw/master/screenshot/zfb.jpg"/>



