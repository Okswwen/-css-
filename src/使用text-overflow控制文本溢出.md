/* 使用text-overflow控制文本溢出 */


### text-overflow

包括挡寒

```scss
对于单行的设置

.sl-ellipsis {
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

对于多行的设置

.ml-ellipsis {
	display: -webkit-box;
	overflow: hidden;
	text-overflow: ellipsis;
	-webkit-line-clamp: 3;
	/* autoprefixer: off */
	-webkit-box-orient: vertical;
	/* autoprefixer: on */
}
```
