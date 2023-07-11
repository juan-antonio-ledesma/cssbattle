# #21 SitePoint Logo

<p>
  <sup>
    <a href="https://cssbattle.dev/play/21"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#21 SitePoint Logo](https://cssbattle.dev/targets/21.png)

## Solutions

```html
<div class="orange"></div>
<div class="blue"></div>
<style>
  body {
    background: #222;
  }
  div {
    position: absolute;
    width: 30px;
    height: 100px;
    border-radius: 0 0 0 10px;
  }
  div::after {
    content: '';
    position: absolute;
    top: 50px;
    left: 30px;
    width: 30px;
    height: 70px;
    transform: rotate(90deg);
    border-radius: 5px 0 0 0;
  }
  .orange {
    top: 58px;
    left: 155px;
    background: #f2994a;
    transform: rotate(45deg);
  }
  .orange::after {
    background: #f2994a;
  }
  .blue {
    top: 142px;
    left: 213px;
    background: #2d9cdb;
    transform: rotate(225deg);
  }
  .blue::after {
    background: #2d9cdb;
  }
</style>
```

```html
<a><a b><style>*{background:#222}a{position:absolute;top:58;left:155;width:30;height:100;background:#f2994a;border-radius:0 0 0 10px;transform:rotate(45deg)}a:after{content:'';position:fixed;top:50;left:30;width:30;height:70;background:#f2994a;border-radius:5px 0 0 0;transform:rotate(90deg)}a[b]{top:142;left:213;background:#2d9cdb;transform:rotate(225deg)}a[b]:after{background:#2d9cdb
```
