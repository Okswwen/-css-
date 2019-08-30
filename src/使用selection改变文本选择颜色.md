/* 使用::selection改变文本选择颜色*/

### ::selection

```scss
通过::selection根据主题颜色自定义文本选择颜色

// 设置全局的主题色
::selection {
	background-color: $purple;
	color: #fff;
}
.select-color {
	line-height: 50px;
	font-weight: bold;
	font-size: 30px;
	color: $red;
}
// 仅仅针对某个设置主题色
.special::selection {
	background-color: $green;
}

```
