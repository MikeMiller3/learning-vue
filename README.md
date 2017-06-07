# learning-vue
vue可以使用以下方式的模版：
1.DOM模版
## 2.字符串模版
	## 2.1 <script type="text/x-template">
	## 2.2 JavaScript内联模版字符串
	## 2.3 vue组件
当使用 DOM 作为模版时（例如，将 el 选项挂载到一个已存在的元素上）, 你会受到 HTML 的一些限制，因为 Vue 只有在浏览器解析和标准化 HTML 后才能获取模版内容。尤其像这些元素 <ul> ，<ol>，<table> ，<select> 限制了能被它包裹的元素， 而一些像 <option> 这样的元素只能出现在某些其它元素内部。使用字符串模版不存在该问题。因此，有必要的话请使用字符串模版。