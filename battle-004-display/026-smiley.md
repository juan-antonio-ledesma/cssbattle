# #26 Smiley

<p>
  <sup>
    <a href="https://cssbattle.dev/play/26"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#26 Smiley](https://cssbattle.dev/targets/26.png)

## Solutions

```html
<div class="eye is-left"></div>
<div class="eye is-right"></div>
<div class="mouth"></div>
<style>
  body {
    background: #6592cf;
  }
  div {
    position: absolute;
    width: 80px;
    height: 40px;
    border-radius: 60px 60px 0 0;
    border: 20px solid #060f55;
    border-bottom: 0;
  }
  .eye.is-left {
    top: 40px;
    left: 40px;
  }
  .eye.is-right {
    top: 40px;
    left: 240px;
  }
  .mouth {
    top: 200px;
    left: 140px;
    transform: scale(-1);
  }
</style>
```

```html
<a><a b><a c><style>*{background:#6592cf}a{position:fixed;top:40;left:40;width:80;height:40;border-radius:60px 60px 0 0;border:20px solid#060f55;border-bottom:0}[b]{top:40;left:240}[c]{top:200;left:140;transform:scale(-1)
```
