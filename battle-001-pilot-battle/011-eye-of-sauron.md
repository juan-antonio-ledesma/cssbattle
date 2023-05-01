# #11 Eye of Sauron

<p>
  <sup>
    <a href="https://cssbattle.dev/play/11"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#11 Eye of Sauron](https://cssbattle.dev/targets/11.png)

## Solutions

```html
<div></div>
<style>
  body {
    background: #191210;
    display: grid;
    place-items: center;
  }
  div {
    height: 50px;
    width: 50px;
    background: #84271c;
    border: 25px solid #191210;
    border-radius: 50%;
    box-shadow: 0 0 0 20px #eca03d;
    position: relative;
  }
  div::before,
  div::after {
    content: '';
    position: absolute;
    height: 30px;
    width: 60px;
    border-radius: 0 0 50px 50px;
    border: 20px solid #eca03d;
    border-top: 0;
  }
  div::before {
    top: 25px;
    left: -125px;
  }
  div::after {
    top: -25px;
    right: -125px;
    transform: rotate(180deg);
  }
</style>
```

```html
<p><a a><a b><style>body{background:#191210;display:grid;place-items:center}p{height:50;width:50;background:#84271c;border:25px solid#191210;border-radius:50%;box-shadow:0 0 0 20px#eca03d}a[a],a[b]{position:fixed;height:30;width:60;border-radius:0 0 50px 50px;border:20px solid#eca03d;border-top:0}a[a]{top:150;left:50}a[b]{top:100;right:50;transform:rotate(180deg)
```
