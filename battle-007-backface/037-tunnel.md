# #37 Tunnel

<p>
  <sup>
    <a href="https://cssbattle.dev/play/37"><strong>GO TO THE PROBLEM</strong></a>
  </sup>
</p>

![#37 Tunnel](https://cssbattle.dev/targets/37.png)

## Solutions

```html
<div class="square is-big">
  <div class="square is-medium">
    <div class="square is-small"></div>
  </div>
</div>
<style>
  body {
    background: #6592cf;
    display: grid;
    place-items: center;
  }
  .square {
    width: 250px;
    height: 250px;
    display: grid;
    place-items: center;
  }
  .square.is-big {
    background: #243d83;
  }
  .square.is-medium {
    background: #6592cf;
    transform: scale(0.6) rotate(15deg);
  }
  .square.is-small {
    background: #243d83;
    transform: scale(0.5) rotate(15deg);
  }
</style>
```

```html
<b><b b><b c><style>body{background:#6592CF;display:grid;place-items:center}b{width:250;height:250;background:#243D83;display:grid;place-items:center}[b]{background:#6592CF;transform:scale(.6)rotate(15deg)}[c]{transform:scale(.5)rotate(15deg)
```
