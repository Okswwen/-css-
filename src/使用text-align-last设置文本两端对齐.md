/* 使用text-align-last设置文本两端对齐 */

通过text-align-last 设置文本来那个段对齐

### text-align-last

```scss
.justify-text {
	li {
		margin-top: 5px;
		padding: 0 20px;
		width: 100px;
		height: 40px;
		background-color: $red;
		line-height: 40px;
		text-align-last: justify;
		color: #fff;
		&:first-child {
			margin-top: 0;
		}
	}
}
```

<img src="./images/text-align-last.png"/>