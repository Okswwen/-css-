### 使用transform描绘1px边框

```scss
.onepx-border {
	margin-top: 10px;
	width: 200px;
	height: 80px;
	cursor: pointer;
	line-height: 80px;
	text-align: center;
	font-weight: bold;
	font-size: 50px;
	color: $red;
	&:first-child {
		margin-top: 0;
	}
}
.normal {
	border: 1px solid $red;
}
.thin {
	position: relative;
	&::after {
		position: absolute;
		left: 0;
		top: 0;
		border: 1px solid $red;
		width: 200%;
		height: 200%;
		content: "";
		transform: scale(.5);
		transform-origin: left top;
	}
}

```