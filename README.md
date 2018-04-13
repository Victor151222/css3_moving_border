**原理**：使用`clip`/`clip-path`属性对伪元素`before`和`after`编写的盒子进行裁切，用通过`animation`动画来让它们运动起来。

**注意**：

1. `clip`在`HTML5`中已经被废弃了(依然可用)，取而代之的是`clip-path`。

2. `clip:rect`与`clip-path: inset`的裁剪方式不同。一个是计算裁剪后的尺寸，一个是计算被裁剪的尺寸。

   ```css
   clip:rect(50px 250px 250px 50px);
   =clip-path: inset(50px 50px 50px 50px);
   ```

   > 参考文献
   >
   > https://segmentfault.com/a/1190000006871772
   >
   > http://yunkus.com/css-clip-path/
   >
   > https://www.qdfuns.com/article/25583/0275db020eef39e51278fa334b24543b.html