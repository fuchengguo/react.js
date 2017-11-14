# React

[React 菜鸟教程](http://www.runoob.com/react/react-tutorial.html)

# 引入

```js
<!--react-核心文件-->
<script src="../js/react.js"></script>
<!--react操作虚拟DOM的文件-->
<script src="../js/react-dom.js"></script>
```
|JS|描述|
|-|-|
|react.min.js|React 的核心库|
|react-dom.min.js|提供与 DOM 相关的功能|
|babel.min.js|Babel 可以将 ES6 代码转为 ES5 代码，这样我们就能在目前不支持 ES6 浏览器上执行 React 代码。Babel 内嵌了对 JSX 的支持。通过将 Babel 和 babel-sublime 包（package）一同使用可以让源码的语法渲染上升到一个全新的水平。|

# Vue/React

## Vue
```js
new Vue({
	el: "#demo",
	/*render: function(createElement) {
		return createElement("h1", "hello world")
	},*/
	data: {
		content: "hello world!"
	},

	template: `
		<div>
			<h1>{{content}}</h1>
		</div>
	`
})
```

## React
```js
ReactDOM.render(
	//必须只能有一个跟节点
	<div>
		<h1>hello world</h1>
		<h1>hello world</h1>
	</div>,
	//el
	document.querySelector("#demo")
)
```

# 表达式


