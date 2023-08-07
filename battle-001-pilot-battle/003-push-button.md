# #3 Push Button

<p>
  <sup>
    <a href="https://cssbattle.dev/play/3"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#3 Push Button](https://cssbattle.dev/targets/3.png)

## Solutions

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
    inset: 50%;
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
<p a><p b><p c><style>*{background:#6592cf}p{margin:0;position:fixed;inset:50%;transform:translate(-50%,-50%)}p:not([a]){border-radius:50%}[a]{width:300;height:150;background:#243d83}[b]{width:150;height:150;background:#243d83;border:50px solid#6592cf}[c]{width:50;height:50;background:#eeb850
```
