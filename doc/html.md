# html

1. html 中的标签和元素是什么？

<details>
<summary>答案</summary>

浏览器渲染网页时，会把 HTML 源码解析成一个标签树，每个标签都是树的一个节点（node）。这种节点就称为网页元素（element）。所以，“标签”和“元素”基本上是同义词，只是使用的场合不一样：标签是从源码角度来看，元素是从编程角度来看，比如<p>标签对应网页的p元素。
</details>
<br><br>

2. 块级元素（block）和行内元素（inline）有什么区别？

<details>
<summary>答案</summary>

* 块级元素默认占据一个独立的区域，在网页上会自动另起一行，占据 100% 的宽度；行内元素默认与其他元素在同一行，不产生换行。
* css 样式中 width 和 height 属性对 行内元素无效，padding 和 margin 的上下方向对行内元素失效；而块级元素没有这个问题。
</details>
<br><br>

