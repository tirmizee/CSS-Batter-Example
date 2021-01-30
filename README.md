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

### Ex.3 https://cssbattle.dev/play/3

```html
<div class="contrainer">
  <div a></div>
  <div b></div>
  <div c></div>
  <div d></div>
</div>
```

```css
<style>
  body {
     background:#6592CF;
  }
  
  .contrainer {
	position : relative;
  }
  
  div[a] {
    width: 300px;
    height: 150px;
    background: #243D83;
    position : absolute;
	top : 67px;
    left : 42px;
  }
  
  div[b] {
    width: 250px;
    height: 250px;
    border-radius : 125px;
    background:#6592CF;
    position : absolute;
    top : 16px;
    left : 66px;
  }
  
  div[c] {
    width: 150px;
    height: 150px;
    border-radius : 75px;
    position : absolute;
    background:#243D83;
    top : 67px;
    left : 117px;
  }
  
  div[d] {
    width: 50px;
    height: 50px;
    border-radius : 25px;
    position : absolute;
    background: #EEB850;
    top : 117px;
    left : 167px;
  }
  
</style>

```


