# #42 Baby

<p>
  <sup>
    <a href="https://cssbattle.dev/play/42"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#42 Baby](https://cssbattle.dev/targets/42.png)

## Solutions

```html
<div class="head">
  <div class="hair"></div>
  <div class="eye"></div>
  <div class="mouth"></div>
</div>
<style>
  body {
    background: #293462;
    display: grid;
    place-items: center;
  }
  .head {
    width: 200px;
    height: 200px;
    background: #fe5f55;
    border-radius: 100px 100px 50px 50px;
    position: relative;
    overflow: hidden;
  }
  .hair,
  .eye,
  .mouth {
    position: absolute;
    background: #fff1c1;
  }
  .hair {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    top: -50px;
    box-shadow: 100px 0 #fff1c1;
  }
  .eye {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    top: 90px;
    left: 20px;
    box-shadow: 100px 0 #fff1c1;
  }
  .mouth {
    width: 40px;
    height: 10px;
    border-radius: 10px;
    top: 170px;
    left: 80px;
  }
</style>
```

```html
<a><b h></b><b e></b><b m><style>body{background:#293462;display:grid;place-items:center}a{width:200;height:200;background:#fe5f55;border-radius:100px 100px 50px 50px;position:relative;overflow:hidden}[h],[e],[m]{position:absolute;background:#fff1c1;}[h]{width:100;height:100;border-radius:50%;top:-50;box-shadow:100px 0#fff1c1}[e]{width:60;height:60;border-radius:50%;top:90;left:20;box-shadow:100px 0#fff1c1}[m]{width:40;height:10;border-radius:10px;top:170;left:80
```
