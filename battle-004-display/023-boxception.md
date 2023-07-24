# #23 Boxception

<p>
  <sup>
    <a href="https://cssbattle.dev/play/23"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#23 Boxception](https://cssbattle.dev/targets/23.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: #f3ac3c;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 200px;
    background: conic-gradient(from -90deg, #1a4341 270deg, #998235 270deg);
    position: relative;
  }
  div::after {
    content: '';
    position: absolute;
    left: 50px;
    bottom: 0;
    width: 50px;
    height: 50px;
    background: #f3ac3c;
  }
</style>
```

```html
<p><a><style>*{background:#f3ac3c}p{width:200;height:200;background:conic-gradient(from -90deg,#1a4341 270deg,#998235 270deg);position:fixed;top:34;left:100}a{position:fixed;left:150;bottom:50;width:50;height:50;
```
