# #12 Wiggly Moustache

<p>
  <sup>
    <a href="https://cssbattle.dev/play/12"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#12 Wiggly Moustache](https://cssbattle.dev/targets/12.png)

## Solutions

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #f5d6b4;
  }
  div {
    height: 30px;
    width: 60px;
    border-radius: 0 0 60px 60px;
    border: 20px solid #d86f45;
    border-top: 0;
    position: absolute;
  }
  div::after {
    content: '';
    width: 20px;
    height: 20px;
    background: #d86f45;
    position: absolute;
    left: -20px;
    top: -10px;
    border-radius: 10px;
    box-shadow: 80px 0 #d86f45;
  }
  div[a] {
    top: 150px;
    left: 70px;
  }
  div[b] {
    transform: rotate(180deg);
    top: 100px;
    left: 150px;
  }
  div[c] {
    top: 150px;
    right: 70px;
  }
</style>
```

```html
<a a><a b><a c><a d><style>*{background:#f5d6b4}a{height:30;width:60;border-radius:0 0 60px 60px;border:20px solid#d86f45;border-top:0;position:fixed;top:150}[a]{left:70}[b]{transform:scale(-1);top:100;left:150}[c]{right:70}[d]{width:20;height:20;left:70;top:140;border-radius:50%;background:#D86F45;border:0;box-shadow:240px 0#d86f45
```
