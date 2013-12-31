-moz 就不写了，直接用 chrome 看吧！

# Transition(过渡) #

Internet Explorer 9 以及更早版本的浏览器不支持 transition 属性。

<ol>
  <li>transition-property:all (initial value)</li>
  <li>transition-duration: 0s</li>
  <li>transition-timing-function: ease</li>
  <li>transition-delay: 0s</li>
</ol>

<b>transition-timing-function</b>

<ul>
  <li>linear: 匀速 ( cubic-bezier(0,0,1,1) )</li>
  <li>ease: 慢速开始，然后变快，然后慢速结束的过渡效果 ( cubic-bezier(0.25,0.1,0.25,1) )</li>
  <li>ease-in: 慢速开始过渡效果 ( cubic-bezier(0.42,0,1,1) )</li>
  <li>ease-out: 慢速结束的过渡效果 ( cubic-bezier(0,0,0.58,1) )</li>
  <li>ease-in-out: 慢速开始和结束的过渡效果 ( cubic-bezier(0.42,0,0.58,1) )</li>
  <li>cubic-bezier(n,n,n,n): 在 cubic-bezier 函数中定义自己的值。可能的值是 0 至 1 之间的数值。</li>
</ul>

<code>cubic-bezier</code>贝塞尔曲线 http://matthewlein.com/ceaser/

# Transform(变换) #

<b>-webkit-transform-style: preserve-3d</b> (This is an experimental technology)

变换 3d 场景

<b>-webkit-perspective</b>

perspective 属性定义 3D 元素距视图的距离，以像素计。该属性允许您改变 3D 元素查看 3D 元素的视图。