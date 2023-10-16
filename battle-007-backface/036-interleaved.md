# #36 Interleaved

<p>
  <sup>
    <a href="https://cssbattle.dev/play/36"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#36 Interleaved](https://cssbattle.dev/targets/36.png)

## Solutions

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #1a4341;
    margin: 0;
    display: flex;
    justify-content: space-evenly;
  }
  div {
    width: 50px;
    height: 200px;
  }
  div:nth-child(odd) {
    align-self: flex-end;
    background: #f3ac3c;
    border-radius: 50px 50px 0 0;
  }
  div:nth-child(even) {
    background: #998235;
    border-radius: 0 0 50px 50px;
  }
</style>
```

```html
<a><a b><style>*{background:#1A4341}a{position:fixed;width:50;height:200;top:0;left:100;border-radius:0 0 25px 25px;background:#998235;box-shadow:150px 0#998235}[b]{top:100;left:25;border-radius:25px 25px 0 0;background:#F3AC3C;box-shadow:150px 0#F3AC3C,300px 0#F3AC3C
```
