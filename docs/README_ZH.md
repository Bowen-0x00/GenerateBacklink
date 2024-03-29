# Quicker Actions

[English](../README.md) | [简体中文](./README_ZH.md)

这个仓库是用于生成回链的一些工具，包括quicker动作、Zotero js脚本等。

实现了一键获得原文（图片、文字）和 回链的功能，如生成视频画面和对应时间戳的回链、PPT画面和对应页码的回链、PDF画面和对应位置的回链。

搭配另2个仓库（插入图片/文字、处理回链）可以实现一键摘录图片/文字并附上回链，然后点击链接跳转回原文处的功能。

## 使用

### 视频摘录

#### 准备
1. 设置potplayer快捷键（如果你要修改为其他的快捷键，需要把quicker动作中设置的快捷键一起改）
   1. <img src="../images/potplayer preference.PNG">
   2. <img src="../images/potplayer keyboard.PNG">
2. 安装quicker软件
3. 导入动作
   1. 右键图标，点击场景与动作<img src="../images/右键.PNG" width="150px">
   2. 在动作页右键，点击导入动作<img src="../images/导入动作.PNG" width="300px">
   3. 选择json文件 [add image and link by json.json](../actions/视频摘录/add%20image%20and%20link%20by%20json.json)、[add image and link by url.json](../actions/视频摘录/add%20image%20and%20link%20by%20url.json)
4. 给动作设置快捷键或者轮盘

#### 使用

1. potplayer播放视频中（无论是否暂停）按给quicker脚本设置的快捷键（不是potplayer中设置的快捷键）
2. 之后在笔记软件中可以是粘贴（对应add image and link by json.json）或自动添加（对应add image and link by url.json）


### PDF摘录

#### Bookxnote

#### Zotero

#### 其他

### PPT摘录

步骤同[视频摘录](#视频摘录)，不过动作为：
#### 动作

[get current slide link.json](../actions/PPT摘录/get%20current%20slide%20link.json)


## 问题、反馈、创意

欢迎联系我，如果：

- 遇到使用问题
- 建议与反馈
- 交流沟通有趣的想法、新的feature

沟通渠道可以是：

- github issue
- 邮件
- B站留言或私信
- 我的个人联系方式 (微信、qq)

## 赞助

如果你觉得我做的这些修改对你有所帮助，欢迎评论、留言。

你也可以赞助我一杯咖啡：

- 微信赞助码 
  <img src="../images/赞助码.jpg" width="200px">
- ko-fi
  <a href='https://ko-fi.com/G2G3SY16R' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
