# 订阅阅读器测试

##javascript 测试框架 
  jasmine.js
  
##测试内容
  1、RSS Feeds测试用例：确定allFeeds变量已经声明并不为空，allFeeds中每个元素的name、url属性均被定义且不为空。
  2、The menu测试用例：确定菜单栏在默认情况下为隐藏状态，点击menuicon实现菜单的显示隐藏。根据实现逻辑，主要为判断body上class "menu-hidden"是否存在。
  3、Initial Entries测试用例：调用并执行loadFeed函数后， 在.feed容器中至少存在一个.entry元素。
  4、New Feed Selection测试用例：确定loadFeed函数加载新内容时后，.feed容器内容会相应改变。
  
##测试结果
  直接运行index.html，jasmine.js反馈结果均正确。
