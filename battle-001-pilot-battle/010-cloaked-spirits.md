# #10 Cloaked Spirits

<p>
  <sup>
    <a href="https://cssbattle.dev/play/10"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#10 Cloaked Spirits](https://cssbattle.dev/targets/10.png)

## Solutions

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #62306d;
  }
  div {
    position: absolute;
    inset: 200px 50px;
    width: 100px;
    height: 200px;
    background: #f7ec7d;
  }
  div::after {
    content: '';
    position: absolute;
    top: -50px;
    width: 60px;
    height: 60px;
    border-radius: 50%;
  }
  div[a]::after,
  div[c]::after {
    background: #e38f66;
    border: 20px solid #aa445f;
  }
  div[b] {
    inset: 100px 150px;
  }
  div[b]::after {
    background: #aa445f;
    border: 20px solid #e38f66;
  }
  div[c] {
    left: 250px;
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#62306D}a{position:fixed;top:200;left:50;width:100;height:200;background:#f7ec7d}a:after{content:'';position:absolute;top:-50;width:60;height:60;background:#e38f66;border-radius:50%;border:20px solid#aa445f}[b]{top:100;left:150}[b]:after{background:#aa445f;border-color:e38f66}[c]{left:250
```
