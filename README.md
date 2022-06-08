# heimaH5
制作移动端黑马页面 (flex + rem + flexible.js + LESS)


flexible.js
- 不再需要在不同屏幕下写不同的媒体查询，因为里面js做了处理
- 原理是将当前设备划分为10等份，但在不同设备下，比例还是一致
- 我们要做的就是确定当前设备的html文字大小即可
- 比如当前设计稿为 750px，我们只需要将html文字大小设置为75px
- 里面页面元素rem的值为 页面元素 px的值 / 75

# 代码规范
属性书写顺序
- 布局定位属性：display、position、float
- 尺寸属性：width、height、margin
- 文本属性：color、font、text-align
- 其他属性：content、cursor、box-shadow

注意：id选择器和 !important 应该避免使用， 权重过高

现在前端设计师可以直接慕客和蓝湖测量取值

# swiper插件
- 用来处理轮播图的一系列操作
使用步骤：
- 下载需要的css和js文件
- 官网找到类似案例，复制html结构，css样式，js语法
- 根据需求定制修改模块即可

