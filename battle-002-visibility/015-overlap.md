# #15 Overlap

<p>
  <sup>
    <a href="https://cssbattle.dev/play/15"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#15 Overlap](https://cssbattle.dev/targets/15.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: #09042a;
  }
  div,
  div:after {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    position: absolute;
  }
  div {
    top: 75px;
    left: 75px;
    background: #7b3f61;
    box-shadow: 100px 0 0 0 #e78481;
    overflow: hidden;
  }
  div::after {
    content: '';
    background: #09042a;
    left: 100px;
  }
</style>
```

```html
<a><style>*{background:#09042a}a,a:after{width:150;height:150;border-radius:50%;position:fixed;background:#7b3f61;left:75}a{top:75;box-shadow:100px 0 0 0#e78481;overflow:hidden}a:after{content:'';background:#09042a;left:100
```
