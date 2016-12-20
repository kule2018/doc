# 滚动条控制  
滚动条分window和dom两种，让我一个一个举例说明。

## window滚动条

读取：
```javascript
// IE > 8，以及其他现代浏览器
console.log(window.pageXOffset); 
console.log(window.pageYOffset);

// IE <= 8
console.log(document.body.scrollLeft); 
console.log(document.body.scrollTop);
```
设置:
```javascript
window.scroll(x, y);
```


## dom元素的滚动条

读取：
```javascript

console.log(window.scrollTop); 
console.log(window.scrollLeft);

```
设置:
```javascript
window.scrollTop = 100; 
window.scrollLeft = 100;
```
