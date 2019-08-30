/*
* 移动端的布局，使用rem需要通过js设置不同屏幕的font-size，自适应大小
* 使用vw calc() 可以匹配屏幕
* 配合rem
* 兼容性查看 https://caniuse.com/#search=vw

*/

/* 基于ui width = 750px DPR = 2 */

```css

html {
  font-size: calc(100vw / 7.5)
}
```
