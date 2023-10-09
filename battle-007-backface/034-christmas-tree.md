# #34 Christmas Tree

<p>
  <sup>
    <a href="https://cssbattle.dev/play/34"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#34 Christmas Tree](https://cssbattle.dev/targets/34.png)

## Solutions

```html
<div class="third"></div>
<div class="second"></div>
<div class="first"></div>
<style>
  body {
    background: #007065;
  }
  div {
    position: absolute;
    left: 75;
    width: 250;
    height: 100;
    clip-path: polygon(50% 0, 0 100%, 100% 100%);
  }
  .third {
    top: 150;
    background: #00a79d;
  }
  .second {
    top: 100;
    background: #f5c181;
  }
  .first {
    top: 50;
    background: #ffeecf;
  }
</style>
```

```html
<a><a b><a c><style>*{background:#007065}a{position:fixed;left:75;width:250;height:100;clip-path:polygon(50% 0,0 100%,100% 100%);top:150;background:#00a79d}[b]{top:100;background:#f5c181}[c]{top:50;background:#ffeecf}
```
