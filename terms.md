Page() - 微信小程序的基本页面构造函数
wx.request() - 微信提供的网络请求
getApp() - 获取小程序实例的方法
setData() - 更新页面数据并触发重新渲染的方法
toggleplay() - 播放/暂停切换
playnext() - 播放下一首
seekmusic() - 歌曲进度跳转
setplaylist() - 设置当前播放列表
shuffleplay() - 随机播放模式
playall() - 播放所有歌曲
curplay - 当前正在播放的歌曲
playing - 播放状态
playtype - 播放模式类型
globalStop - 全局暂停状态
music - 当前播放的音乐对象
id - 歌曲唯一标识符
st/starred - 歌曲收藏状态
list_sf - 混洗后的播放列表引用
index_am - 当前歌曲索引
common - 公共工具函数模块
util.js - 工具类js文件
data - 存储页面数据的对象
value, prevalue - 输入框值及其之前的状态值
loading - 标识加载状态的布尔变量
recent - 存储最近搜索记录的数组
inputext(e) - 输入框输入事件处理函数
playmusic(event) - 点击播放音乐事件处理函数
searhFrecent(e), searhFinput(e) - 快速搜索和输入框搜索事件处理函数
event.currentTarget.dataset - 获取事件源组件上自定义属性集
wx.showToast() - 显示消息提示框
search(name) - 执行搜索操作的函数
tabtype(e) - 切换搜索类型的事件处理函数
clear_kw() - 清除关键词及重置搜索结果
del_research(e) - 删除特定历史搜索记录
data - 存储页面数据的对象
value, prevalue - 输入框值及其之前的状态值
loading - 标识加载状态的布尔变量
recent - 存储最近搜索记录的数组
