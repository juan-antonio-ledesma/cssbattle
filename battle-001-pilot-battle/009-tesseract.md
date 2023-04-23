# #9 Tesseract

<p>
  <sup>
    <a href="https://cssbattle.dev/play/9"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#9 Tesseract](https://cssbattle.dev/targets/9.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: linear-gradient(
      #222730 25%,
      #4caab3 25%,
      #4caab3 75%,
      #222730 75%
    );
    display: grid;
    place-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    background: #4caab3;
    box-shadow: 0 0 0 50px #222730;
    transform: rotate(45deg);
    display: grid;
    place-items: center;
  }
  div::before {
    content: '';
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #393e46;
  }
</style>
```

```html
<p><style>body{background:linear-gradient(#222730 25%,#4caab3 25%,#4caab3 75%,#222730 75%);display:grid;place-items:center}p{width:150;height:150;background:#4caab3;box-shadow:0 0 0 50px#222730;transform:rotate(45deg);display:grid;place-items:center}p:before{content:'';width:50;height:50;border-radius:50%;background:#393e46
```

---

```html
<div a></div>
<div b></div>
<div c></div>
<style>
  body {
    background: #222730;
  }
  div {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  div[a] {
    width: 100%;
    height: 150px;
    background: #4caab3;
  }
  div[b] {
    width: 150px;
    height: 150px;
    background: #4caab3;
    transform: translate(-50%, -50%) rotate(45deg);
    border: solid 50px #222730;
    border-radius: 0.1px;
  }
  div[c] {
    width: 50px;
    height: 50px;
    background: #393e46;
    border-radius: 50%;
  }
</style>
```

```html
<a a><a b><a c><style>*{background:#222730}a{position:fixed;top:50%;left:50%;transform:translate(-50%,-50%)}a[a]{width:100%;height:150;background:#4caab3}a[b]{width:150;height:150;background:#4caab3;transform:translate(-50%,-50%)rotate(45deg);border:solid 50px#222730;border-radius:0.1px}a[c]{width:50;height:50;background:#393e46;border-radius:50%
```
