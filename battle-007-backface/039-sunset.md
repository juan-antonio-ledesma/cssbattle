# #39 Sunset

<p>
  <sup>
    <a href="https://cssbattle.dev/play/39"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#39 Sunset](https://cssbattle.dev/targets/39.png)

## Solutions

```html
<div class="figure-a"></div>
<div class="figure-b"></div>
<style>
  body {
    background: #1a4341;
  }
  div {
    position: absolute;
    inset: 50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
  }
  .figure-a {
    width: 200px;
    height: 200px;
    background: linear-gradient(
      #998235 15%,
      #1a4341 15%,
      #1a4341 85%,
      #998235 85%
    );
  }
  .figure-b {
    width: 250px;
    height: 250px;
    background: linear-gradient(
      transparent 75px,
      #f3ac3c 75px,
      #f3ac3c 95px,
      #1a4341 95px,
      #1a4341 115px,
      #f3ac3c 115px,
      #f3ac3c 135px,
      #1a4341 135px,
      #1a4341 155px,
      #f3ac3c 155px,
      #f3ac3c 175px,
      transparent 175px
    );
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#1A4341}a{position:fixed;width:200;height:200;top:50;background:#998235}[a],[b]{border-radius:50%}[a]{left:100}[b]{background:#F3AC3C;width:250;height:250;top:25;left:75;clip:rect(75,250,175,0)}[c]{background:#1A4341;width:385;height:20;top:80;box-shadow:0 40px#1A4341,0 80px#1A4341,0 120px#1A4341
```
