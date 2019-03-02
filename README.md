# Vue2.5开发去哪儿网App 从零基础入门到实战项目

> 从理论到项目，一个课程涵盖Vue各个层面的基础知识和开发技巧

## 工程启动流程

``` bash
# 切换到课程章节对应的分支上（重要！）
git checkout 分支名

# 安装项目依赖
npm install

# 启动开发环境服务器
npm run dev
```

## 常见问题汇总

1. 在手机测试详情页面，向下滚动的时候头部header不会出现,在电脑端是可以的  
解答：scrollTop的兼容性问题。const top = document.documentElement.scrollTop || document.body.scrollTop || window.pageYOffset

### 如果上面的解答依然无法解答你的问题，请在慕课网答疑区留言。非课程相关问题，可以通过下面的微信联系到 Dell Lee ～

<img src="https://git1.imooc.com/Project/coding-203/raw/master/wechat.jpg" width=300 height=400 />
