# CSS-Batter-Example

### Ex.1 https://cssbattle.dev/play/1

```html

<div></div>

```

```css

<style>
  body {
    background: #5d3a3a;
  }
  div {
    width: 200px;
    height: 200px;
    background: #b5e0ba;
    position : relative;
    top : -8px;
    left : -9px;
  }
</style>

```

### Ex.2 https://cssbattle.dev/play/2

```html
<div></div>
<div></div>
<div></div>
<div></div>
```

```css
<style>
  body {
    background: #62374e;
  }
  div {
    width: 50px;
    height: 50px;
    background: #fdc57b;
    position :absolute;
  }
  div:nth-child(1) {
    top : 50px;
    left : 50px
 
  }
  div:nth-child(2) {
    top : 50px;
    right : 50px
  }
  div:nth-child(3) {
    top : 200px;
    right : 50px
  }
   div:nth-child(4) {
    top : 200px;
    right : 300px
  }

</style>
```

