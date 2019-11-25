/* css三角形*/

### css三角形


```scss
.triangle {
  width: 0;
  height: 0;
  border-top: 20px solid #333;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
}

/**
* 等边三角形
* @param {String} 尺寸
* @param {Color} 颜色
* @param {String} 方向
*/
@mixin triangle($size: 5px, $color: rgba(0, 0, 0, 0.6), $dir: bottom) {
  width: 0;
  height: 0;
  border-style: solid;

  @if (bottom==$dir) {
    border-width: $size $size 0 $size;
    border-color: $color transparent transparent transparent;
  } @else if (top==$dir) {
    border-width: 0 $size $size $size;
    border-color: transparent transparent $color transparent;
  } @else if (right==$dir) {
    border-width: $size 0 $size $size;
    border-color: transparent transparent transparent $color;
  } @else if (left==$dir) {
    border-width: $size $size $size 0;
    border-color: transparent $color transparent transparent;
  }
}


```
