/* 使用transform启动GPU硬件加速*/

### transform

```scss
有时执行动画可能会导致页面卡顿，可在特定元素中使用硬件加速来避免这个问题

有些浏览器，使用position：fixed定位，页面滚动时，会出现抖动的现象，使用此会消除抖动

.elem {
    transform: translate3d(0, 0, 0); /* translateZ(0)亦可 */
}

```
