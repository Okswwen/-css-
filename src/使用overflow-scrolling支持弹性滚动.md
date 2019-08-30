/* 使用overflow-scrolling支持弹性滚动*/

### overflow-scrolling

```scss
iOS页面非body元素的滚动操作会非常卡(Android不会出现此情况)，通过overflow-scrolling:touch调用Safari原生滚动来支持弹性滚动，增加页面滚动的流畅度

body {
    -webkit-overflow-scrolling: touch;
}
.elem {
    overflow: auto;
}

```
