# vuex的简单使用 2016-12-20

##本文适合读者
可以使用vue-cli开发项目

##vuex用来干什么的?
对于vuex简单来说是把vue中`data`参数的数据结构`单独拿了出来`进行`管理`

##为什么单独管理?
当组件关系变得复杂的时候, 如果用prop或者内部的信息传播机制共享数据会使代码结构乱到难以维护, 所以vuex出现了, 使用前提建立在`复杂项目`下, 如果项目内部的组件很少请不要使用vuex, 因为用vuex会有增加代码量(需要写出State, Mutations, Action等代码结构);

##写一个小例子
.首先, 建立一个store.js文件, 放在和入口main.js同级,

```
import Vuex from 'vuex'
Vue.use(Vuex)
```
## State
可以类比原来vue中的data参数; 这些数据放在这主要是为了多组件共享.
.声明state.

.组件读取: 
```javascript
$store.state.
```






