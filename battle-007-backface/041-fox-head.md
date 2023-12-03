# #41 Fox Head

<p>
  <sup>
    <a href="https://cssbattle.dev/play/41"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#41 Fox Head](https://cssbattle.dev/targets/41.png)

## Solutions

```html
<div class="left-side"></div>
<div class="right-side"></div>
<style>
  body {
    background: #293462;
  }
  div {
    position: absolute;
    top: 180px;
    left: 150px;
    width: 50px;
    height: 150px;
    border-radius: 0 40px 0 0;
    box-shadow: 0 -100px #fe5f55;
  }
  div::after {
    content: '';
    height: 30px;
    width: 30px;
    border-radius: 50%;
    background: #293462;
    position: absolute;
    left: 15px;
    top: -40px;
  }
  .right-side {
    left: 200px;
    transform: scaleX(-1);
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#293462}a{position:fixed}[a],[b]{top:180;width:50;height:200;box-shadow:0-100px#FE5F55}[a]{left:150;border-radius:0 40px 0 0}[b]{left:200;border-radius:40px 0 0 0}[c]{top:140;left:165;background:#293462;width:30;height:30;border-radius:50%;box-shadow:40px 0#293462
```
