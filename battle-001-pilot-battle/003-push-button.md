# [#3 Push Button](https://cssbattle.dev/play/3)

![#3 Push Button](https://cssbattle.dev/targets/3.png)

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #6592cf;
  }
  div {
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  div:not(div[a]) {
    border-radius: 50%;
  }
  div[a] {
    width: 300px;
    height: 150px;
    background: #243d83;
  }
  div[b] {
    width: 150px;
    height: 150px;
    background: #243d83;
    border: 50px solid#6592cf;
  }
  div[c] {
    width: 50px;
    height: 50px;
    background: #eeb850;
  }
</style>
```

```html
<p a><p b><p c><style>body{background:#6592cf}p{margin:0;position:fixed;top:50%;left:50%;transform:translate(-50%,-50%)}p:not([a]){border-radius:50%}p[a]{width:300;height:150;background:#243d83}p[b]{width:150;height:150;background:#243d83;border:50px solid#6592cf}p[c]{width:50;height:50;background:#eeb850
```
