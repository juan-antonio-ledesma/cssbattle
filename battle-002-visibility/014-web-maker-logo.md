# #14 Web Maker Logo

<p>
  <sup>
    <a href="https://cssbattle.dev/play/14"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#14 Web Maker Logo](https://cssbattle.dev/targets/14.png)

## Solutions

```html
<div a></div>
<div b></div>
<div c></div>
<div d></div>
<style>
  body {
    background: #f2f2b6;
  }
  div {
    width: 150px;
    height: 130px;
    top: 85px;
    clip-path: polygon(0% 100%, 50% 0%, 100% 100%);
    position: absolute;
  }
  div[a],
  div[c] {
    transform: rotate(180deg);
  }
  div[a],
  div[d] {
    background: #fd4602;
  }
  div[b],
  div[c] {
    background: #ff6d00;
  }
  div[a] {
    left: 80px;
  }
  div[b] {
    left: 190px;
  }
  div[c] {
    left: 60px;
  }
  div[d] {
    left: 170px;
  }
</style>
```

```html
<a a><a b><a c><a d><style>*{background:#f2f2b6}a{width:150;height:130;top:85;clip-path:polygon(0%100%,50%0%,100%100%);position:fixed;background:#fd4602;left:80}[a],[c]{transform:scale(-1)}[b],[c]{background:#ff6d00}[b]{left:190}[c]{left:60}[d]{left:170
```

---

```html
<div a></div>
<div b></div>
<style>
  body {
    background: #f2f2b6;
  }
  div {
    position: absolute;
    top: 85px;
    border-left: 75px solid transparent;
    border-right: 75px solid transparent;
  }
  div[a] {
    left: 60px;
    border-top: 130px solid #ff6d00;
    filter: drop-shadow(20px 0 #fd4602);
  }
  div[b] {
    left: 170px;
    border-top: 130px solid #fd4602;
    filter: drop-shadow(-20px 0 #ff6d00);
    transform: rotate(180deg);
  }
</style>
```

```html
<a><a b><style>body{background:#f2f2b6}a{position:fixed;top:85;left:60;border-left:solid 75px transparent;border-right:solid 75px transparent;border-top:solid 130px#ff6d00;filter:drop-shadow(20px 0#fd4602)}[b]{left:170;border-top:solid 130px#fd4602;filter:drop-shadow(-20px 0#ff6d00);transform:scale(-1)
```
