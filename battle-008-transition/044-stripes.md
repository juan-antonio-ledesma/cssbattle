# #44 Stripes

<p>
  <sup>
    <a href="https://cssbattle.dev/play/44"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#44 Stripes](https://cssbattle.dev/targets/44.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: #1a4341;
    display: grid;
    place-items: center;
  }
  div {
    width: 160px;
    height: 180px;
    background: repeating-linear-gradient(
      #f3ac3c,
      #f3ac3c 20px,
      #1a4341 20px,
      #1a4341 40px
    );
  }
  div::before {
    content: '';
    width: 300px;
    height: 300px;
    background: #1a4341;
    border-radius: 50%;
    position: absolute;
    left: -150px;
    top: 0;
    box-shadow: 400px 0 #1a4341;
  }
</style>
```

```html
<a><b><style>*{background:#1a4341}b{width:300;height:300;background:#1a4341;border-radius:50%;position:fixed;left:-150;top:0;box-shadow:400px 0#1a4341}a{position:fixed;top:60;left:120;width:160;height:180;background:repeating-linear-gradient(#f3ac3c,#f3ac3c 20px,#1a4341 20px,#1a4341 40px
```
