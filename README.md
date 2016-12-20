# 滚动条控制  
滚动条分window和dom两种，让我一个一个举例说明。

#### window滚动条，读取：
```javascript
console.log(window.pageXOffset); 
console.log(window.pageYOffset);
```
pageXOffset 设置或返回当前页面相对于窗口显示区左上角的 X 位置。pageYOffset 设置或返回当前页面相对于窗口显示区左上角的 Y 位置。
IE 8 及 更早 IE 版本不支持该属性,但可以使用 "document.body.scrollLeft" 和 "document.body.scrollTop" 属性 。
