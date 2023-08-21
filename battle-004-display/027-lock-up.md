# #27 Lock Up

<p>
  <sup>
    <a href="https://cssbattle.dev/play/27"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#27 Lock Up](https://cssbattle.dev/targets/27.png)

## Solutions

```html
<div class="circle"></div>
<div class="circle is-inner"></div>
<style>
  body {
    background: #e38f66;
  }
  .circle {
    position: absolute;
    inset: 50%;
    transform: translate(-50%, -50%);
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: repeating-conic-gradient(
      #f7ec7d,
      #f7ec7d 25%,
      #aa445f 25%,
      #aa445f 50%
    );
    border: 30px solid #aa445f;
  }
  .circle.is-inner {
    background: #aa445f;
    width: 20px;
    height: 20px;
  }
</style>
```

```html
<a><a b><style>*{background:#e38f66}a{position:fixed;border-radius:50%}a{background:#aa445f;width:200;height:200;top:50;left:100}[b]{border:30px solid#f7ec7d;border-left-color:#AA445F;border-right-color:#AA445F;width:80;height:80;top:80;left:130;transform:rotate(45deg
```
