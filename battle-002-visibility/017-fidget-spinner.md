# #17 Fidget Spinner

<p>
  <sup>
    <a href="https://cssbattle.dev/play/17"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#17 Fidget Spinner](https://cssbattle.dev/targets/17.png)

## Solutions

```html
<div class="floor"></div>
<div class="left"></div>
<div class="right"></div>
<div class="top"></div>
<div class="bottom"></div>
<style>
  body {
    background: #09042a;
  }
  div {
    width: 60px;
    height: 60px;
    border: solid 10px;
    border-radius: 50%;
    position: absolute;
  }
  .floor,
  .left,
  .right {
    border-color: #e78481;
    top: 110px;
  }
  .floor {
    width: 40px;
    background: #e78481;
    left: 170px;
    border-radius: 0;
  }
  .left {
    left: 100px;
  }
  .right {
    left: 220px;
  }
  .top,
  .bottom {
    background: #f5bb9c;
    border-color: #09042a;
    left: 160px;
  }
  .top {
    top: 57px;
  }
  .bottom {
    top: 163px;
  }
</style>
```

```html
<a f><a l><a r><a t><a b><style>*{background:#09042a}a{width:60;height:60;border:solid 10px#e78481;border-radius:50%;position:fixed;top:110;left:170}[f]{width:40;background:#e78481;border-radius:0}[l]{left:100}[r]{left:220}[t],[b]{background:#f5bb9c;border-color:#09042a;left:160}[t]{top:57}[b]{top:163
```
