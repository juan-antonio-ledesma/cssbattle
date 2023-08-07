# #25 Blossom

<p>
  <sup>
    <a href="https://cssbattle.dev/play/25"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#25 Blossom](https://cssbattle.dev/targets/25.png)

## Solutions

```html
<div class="green up"></div>
<div class="green down"></div>
<div class="yellow up"></div>
<div class="yellow down"></div>
<style>
  body {
    background: #998235;
  }
  div {
    position: absolute;
  }
  .green {
    height: 100px;
    width: 80px;
    background: #1a4341;
  }
  .green.up {
    border-radius: 0 50px;
    top: 60px;
    left: 110px;
  }
  .green.down {
    border-radius: 50px 0;
    top: 140px;
    left: 210px;
  }
  .yellow {
    height: 60px;
    width: 80px;
    background: #f3ac3c;
  }
  .yellow.up {
    top: 60px;
    left: 210px;
    border-radius: 50px 0;
  }
  .yellow.down {
    top: 180px;
    left: 110px;
    border-radius: 0 50px;
  }
</style>
```

```html
<a a><a b><a c><a d><style>*{background:#998235}a{position:fixed;width:80}[a],[b]{background:#1a4341;height:100}[c],[a]{left:110;border-radius:0 50px}[d],[a]{top:60}[c],[b]{bottom:60}[d],[b]{right:110;border-radius:50px 0}[c],[d]{background:#f3ac3c;height:60
```
