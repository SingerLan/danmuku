>问题或建议，请加QQ群留言。**199580494**

**不看弹幕的请绕行，关注公众号：OK猫开发，获取ok影视最新版，更多功能比此折腾版本好用很多**
请阅读下方文本熟悉使用方法。
## 一、简介
- 支持自定义弹幕
- 支持弹幕时间轴调整
- 支持自定义背景api
- 根据OK影视2.3.4修改
- 修改OK影视2.3.4弹幕越播越快的bug
## 二、功能介绍
### 2.1 自定义弹幕
1. 设置->填入自定义弹幕地址：弹幕json文件
2. 播放带弹幕的资源
3. 如果开启自定义则会根据“弹幕json文件”匹配新的弹幕
### 2.2 自定义背景api
例如：https://raw.githubusercontent.com/SingerLan/json/master/random.png
程序会将random随机替换成0～9任意数字。
>如随机数字是2，实际的背景图是https://raw.githubusercontent.com/SingerLan/json/master/2.png
>![image](https://github.com/SingerLan/danmuku/assets/44799711/9fff238b-8cdd-4dd0-b143-01121598332a)
### 2.2 弹幕时间轴调整
因资源不同，弹幕与视频的时间可能不匹配，故增加时间轴  
- TV：设置->弹幕设置->可调整正负600秒
- 手机：弹幕设置弹窗->可调整正负600秒(可能需要退出视频，重新进入，没有测试过)
## 三、弹幕json文件介绍
```
[{"name":"玫瑰的故事","url":"https://raw.githubusercontent.com/SingerLan/danmuku/main/玫瑰的故事"},
[{"name":"谍影重重","url":"https://raw.githubusercontent.com/SingerLan/danmuku/main/谍影重重/谍影重重.xml"}]]
```
$\color{red} {注意:剧集的url是文件夹地址，电影的url是文件地址} $  
$\color{orange} {注意:剧集文件夹内的文件名必须：E01.xml，E02.xml，E03.xml...} $  
$\color{blue} {注意:剧集电影的文件夹或电影的"name"必须与播放的剧集电影相同，否则无法正确匹配} $

## 四、问题说明

### 4.1 为什么在2.3.4基础上修改？
  OK一直不更新release代码，2.3.7个人感觉播放器解码有点问题。催ok大佬更新

### 4.2 为什么修改自定义背景api？
  想用自己的图片，自己还没有服务器，随机图片只能这么写了，下面是我用的api地址
  > https://raw.githubusercontent.com/SingerLan/json/master/random.png  
  random是固定的  
  自己做格式为：https://*****/random.png  
  $\color{red} {注意:不想使用只能推送壁纸，填其它格式的地址无效} $

## 五、其它说明  
- OK更新本版本相关内容，将删除该app。
- 关注Ok公众号，获取OK接口，资源丰富。

## 六、收费
  本人搜集、收藏B站下架视频弹幕1G以上，韩剧弹幕500M以上，如需要可联系作者（付费）。
  除以上其它内容开放，

## 七、下载
  TV下载地址

## 八、鸣谢
  弹幕爱好者们
