# WIT电子爱好者协会官网管理方法
> 由于官网使用github服务器，因此要求管理人员必须拥有github账号。注册方法自行百度。

### Step1:
* 在浏览器中打开[http://github.com/xjx00/blog](http://github.com/xjx00/blog)并将此项目folk到自己的账号下可以看到出现“blog”仓库。
### Step2：
将用markdown写好的文章头部加入并修改以下代码

```
+++
author = "此处填写作者"
date = "2018-01-16T2:11:24+08:00 按此格式填写时间" 
share = false
draft = false
+++
```
### Step3：
* 在自己folk的项目下找到并打开source分支
* 依次打开content/post文件夹
* 使用“new file”方式新建文件并命名（文件名必须以.md结尾，与文章相关且不能出现中文
* 添加commit注释并点击commit按钮
### Step4：
* commit提交后会出现“Compare & Pullrequest”按钮，点击按钮并添加文章内容注释后提交
### Step5:
* 等待管理员审核并上线发布




