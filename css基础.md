# CSS基础内容
## CSS文字样式（font）
- 学会联想
- 文字大小 font-size
- 文字颜色 color
- 文字对齐方式（水平）text-align
- 文字对齐方式（垂直）vertical-align： top, middle，bottom
- 文字粗细 font-weight: 100-800
- 文字斜体（不建议css，i标签解决）
- 文字在容器垂直居中 height和行高（但是这个是设置给容器的）
## CSS背景样式
- 学会联想
- 背景颜色 background-color: #FF0000;
- 背景图片 background-image: url("");
- 背景尺寸（背景大小）background-size: 70% 100%;
- 背景是否重复 background-repeat: no-repeat;
- 背景位置 background-position: 10px 50%;
## CSS边框
- 学会联想
- 边框多粗、边框是什么类型（虚线，实线）、边框颜色\
  border: 1px solid red;
- 边框分成上下左右四个部分\
  border-left: 1px solid red;\
  border-right: 1px solid red;\
  border-top: 1px solid red;\
  border-bottom: 1px solid red;
- 通过边框分为上下左右四部分，就可以通过边框实现三角形
## CSS盒模型
- 学会联想
- 基本定义：盒模型由一个又一个div组成
```html
    <div>
        <span>你好</span>
        <ul>
            <li>列表1</li>
            <li>列表2</li>
            <li>列表3</li>
        </ul>
    </div>
```
- 盒模型基本定义了解后，那么我们就要学习盒模型的计算规则
- margin:外边距；padding：内边距；边：边框的意思
- 内容部分
- 宽度 = 左边框 + 左内边距 + 内容 + 右内边距 + 有边框
- IE盒模型：
- 我们设置多少就是多少
- 通过盒模型发现，就是针对div标签的一个概念
- div是一个块级元素
- 然后我们学习到display属性
- display: block
- display: inline
- display: inline-block
- display: flex（弹性布局，flex布局）
## CSS浮动float
- 左、右浮动：float: left
- 浮动的影响: 高度塌陷
- 解决方法：overflow: hidden（写在浮动元素的父元素）
- 给父元素设置固定的高度
## 盒模型的对齐
- margin: auto 快速水平居中对齐方式
## 定位 position
```css
div {
  position: relative; /* 相对定位 */
  position: absolute; /* 绝对定位 */
  position: fixed; /* 固定定位 */
}
```
## 拓展内容
- 透明度 opacity （针对容器的透明度）
- rgba(255,255,255,0.1) 前面三个参数：0-255 （针对文字或者容器都可以）
- cursor: point; 设置鼠标的样式
## 学习目标（切记：不要偷懒）
- 1.把该文件内的所有知识点打卡完成
- 2.整合所有学习过的知识点，至少完整的练习3遍或以上上次的作业
