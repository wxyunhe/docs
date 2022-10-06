## 1. Vue3 新特性
## 2. Vue3 与 Vue2 区别
## 3. 双向绑定原理
## 4. Proxy 与 Object. defineProperty 对比
## 5. Composition API
composition api 被称呼为组合式api，优势是关注点分离
## 6. v-show 与 v-if 有什么区别？
## 7. 生命周期
生命周期指组件从创建到销毁的整个流程

## 8. keep-alive
## 9. 组件通信
## 10. 虚拟DOM
## 11. Diff 算法
## 12. key有什么作用？
## 13. $nextTick
## 14. 为什么要用 vuex
这个问题可以拆成两个部分：
1. 什么是 vuex？
	1. vuex 是一个专用于 vue 应用程序开发的状态管理模式 + 库
		1. 专用于 vue 的有什么优势？
			1. 利用 Vue.js 的细粒度数据响应机制来进行高效的状态更新。
			2. 周边支持：vue devtools
		2. 什么模式？
			1. 单向数据流：view -> action -> state -> view[loop]
	2. 采用 **集中式存储** 管理应用的所有组件的状态
	3. 并以相应的规则保证状态以一种 **可预测方式** 发生变化
2. 什么是状态管理模式？
3. 为什么要使用状态管理？
4. 状态管理的发展历程
	1. 

## 15. vuex 原理
## 16. SSR
## 17. vue-router 路由实现原理
## 18. vue-router 有几种路由类型？每种路由类型实现原理
1. abstract mode
2. history mode
3. hash mode
## 19. 项目本地开发完成后部署到服务器后报404是什么原因呢？
大概率可能是配置了 history mode 路由。