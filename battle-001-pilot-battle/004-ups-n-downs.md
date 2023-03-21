# #4 Ups n Downs

<p>
  <sup>
    <a href="https://cssbattle.dev/play/4"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#4 Push Button](https://cssbattle.dev/targets/4.png)

## Solutions

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #62306d;
  }
  div {
    width: 100px;
    height: 100px;
    position: absolute;
    background: #f7ec7d;
    border-radius: 0 0 50% 50%;
  }
  div[a] {
    inset: 150px 50px;
  }
  div[b] {
    transform: rotate(180deg);
    inset: 50px 150px;
  }
  div[c] {
    inset: 150px 250px;
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#62306d}a{width:100;height:100;position:fixed;background:#f7ec7d;border-radius:0 0 50% 50%}a[a]{inset:150px 50px}a[b]{transform:rotate(180deg);inset:50px 150px}a[c]{inset:150px 250px
```
