# #20 Ticket

<p>
  <sup>
    <a href="https://cssbattle.dev/play/20"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#20 Ticket](https://cssbattle.dev/targets/20.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: #62306d;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 100px;
    background: linear-gradient(90deg, #f7ec7d 70%, #e38f66 70%);
    position: relative;
  }
  div::before,
  div::after {
    content: '';
    position: absolute;
    background: #62306d;
    border-radius: 50%;
  }
  div::before {
    top: -20px;
    left: -20px;
    width: 40px;
    height: 40px;
    box-shadow: 200px 0 #62306d, 200px 100px #62306d, 0 100px #62306d;
  }
  div::after {
    top: -10px;
    left: 130px;
    width: 20px;
    height: 20px;
    box-shadow: 0 100px #62306d;
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#62306d}a{position:fixed}a[a]{top:100;left:100;width:200;height:100;background:linear-gradient(90deg,#f7ec7d 70%,#e38f66 70%)}a[b],a[c]{border-radius:50%;background:#62306d}a[b]{top:80;left:80;width:40;height:40;box-shadow:200px 0 #62306d,0 100px#62306d,200px 100px#62306d}a[c]{top:90;left:230;width:20;height:20;box-shadow:0 100px#62306d
```
