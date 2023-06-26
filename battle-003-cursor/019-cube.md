# #19 Cube

<p>
  <sup>
    <a href="https://cssbattle.dev/play/19"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#19 Cube](https://cssbattle.dev/targets/19.png)

## Solutions

```html
<div class="side-left"></div>
<div class="side-center"></div>
<div class="side-right"></div>
<style>
  body {
    background: #0b2429;
  }
  div {
    position: absolute;
  }
  .side-left,
  .side-right {
    top: 80px;
    width: 70px;
    height: 70px;
  }
  .side-left {
    left: 130px;
    background: #998235;
    transform: skewY(-45deg);
  }
  .side-right {
    left: 200px;
    background: #1a4341;
    transform: skewY(45deg);
  }
  .side-center {
    top: 135px;
    left: 150px;
    background: #f3ac3c;
    width: 100px;
    height: 100px;
    transform: rotate(45deg);
  }
</style>
```

```html
<a l><a c><a r><style>*{background:#0b2429}a{position:fixed;top:135;left:150;background:#f3ac3c;width:100;height:100;transform:rotate(45deg)}a[l],a[r]{top:80;width:70;height:70}a[l]{left:130;background:#998235;transform:skewY(-45deg)}a[r]{left:200;background:#1a4341;transform:skewY(45deg)
```
