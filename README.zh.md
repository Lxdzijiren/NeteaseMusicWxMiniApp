<!-- by 蒙一鑫 -->
# 项目安装与启动

### (1) 克隆项目

a. 主项目
```bash
git clone https://github.com/TMyxGames/NeteaseMusicWxMiniApp.git
```

b. 后端项目
```bash
git clone https://github.com/TMyxGames/netmusic-node.git
```

### (2) 安装Node.js

a. 下载地址:https://nodejs.org/en/

b. 检查安装
```bash
node -v
```

### (3) 启动后端

a. 打开终端并切换工作路径到后端文件夹

b. 输入
```bash
npm i
node app.js
```
### (4) 打开主项目

在 ```详情 > 本地设置``` 中勾选 ```不校验合法域名、web-view（业务域名）、TLS版本及HTTPS证书```

### (5) 编译项目


# 项目主要功能和截图

<!-- by 蒙一鑫 -->
### album

![页面截图](picture/QQ20250510-034959.jpg)

音乐播放器的核心功能，包括获取音乐信息、播放控制、分享和页面跳转

- index.js  
    - 定义了数据结构和方法，实现了音乐播放页面的功能

- index.wxml  
    - 实现了音乐播放页面的外观

- index.wxss  
    - 定义了音乐播放界面的组件样式

### artist

![页面截图](picture/QQ20250510-041120.jpg)

歌手详情页面功能，包括歌手信息、歌手作品、专辑以及MV

- index.js  
    - 定义了数据结构和方法，实现了歌手详情页面的功能

- index.wxml  
    - 实现了歌手详情页面的外观

- index.wxss  
    - 定义了歌手详情页面的组件样式

### cloud

云盘功能，用于展示用户在云盘中储存的音乐列表

- index.js  
    - 定义了数据结构和方法，实现了云盘的功能

- index.wxml  
    - 实现了云盘页面的外观

- index.wxss  
    - 定义了云盘页面的组件样式

### djradio

![页面截图](picture/QQ20250510-182955.jpg)

电台详情页面功能，包括电台信息、电台节目列表以及播放控制

- index.js  
    - 定义了数据结构和方法，实现了电台详情页面功能的操作逻辑

- index.wxml  
    - 实现了电台详情页面的外观

- index.wxss  
    - 定义了电台详情页面的组件样式

### fm

![页面截图](picture/QQ20250510-183203.jpg)

私人FM功能，支持根据用户喜好推荐歌曲以及播放控制

- index.js  
    - 定义了数据结构和方法，实现了私人FM播放页面功能的操作逻辑

- index.wxml  
    - 实现了私人FM播放页面的外观

- index.wxss  
    - 定义了私人FM播放页面的组件样式