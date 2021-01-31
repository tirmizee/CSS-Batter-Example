# CSS-Battle-Example

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
<div a>
<div b>
<div c>
<div d>
```

```css
<style>
  body {
    background:#6592CF;
    margin:0;
  }
  
  div[a] {
    width: calc(100% - 100px);
    height: 150px;
    background: #243D83;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
   div[b] {
    width: 250px;
    height: 250px;
    border-radius:175px;
    background: #6592CF;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
  div[c] {
    width: 150px;
    height: 150px;
    border-radius:75px;
    background: #243D83;
    position: relative;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
  div[d] {
    width: 50px;
    height: 50px;
    border-radius:25px;
    background: #EEB850;
    position: absolute;
    left : 50%;
    top : 50%;
    transform:translate(-50%,-50%);
  }
  
</style>

```


### Ex.4 https://cssbattle.dev/play/4

```html
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#62306D;
    display: flex;
    align-items:center;
    justify-content:center;
  }
  
  div:nth-child(1){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:0px 0px 50px 50px;
    margin-top:100px;
  }
  
  div:nth-child(2){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:50px 50px 0px 0px;
    margin-top:-100px;
  }
  
  div:nth-child(3){
    width: 100px;
    height: 100px;
    background:#F7EC7D;
    border-radius:0px 0px 50px 50px;
    margin-top:100px;
  }
  
</style>
```

### Ex.5 https://cssbattle.dev/play/5

```html
  <div></div>
  <div></div>
  <div></div>
```
```css
<style>
  body {
    background:#0B2429;
    display:flex;
    justify-content:center;
    
  }
  div:nth-child(1){
    width: 120px;
    height: 120px;
    background:#F3AC3C;
    border-radius:50% 0px 50% 50%;
    margin-top:82px;
    transform:translate(50%,50%);
    z-index:2;
  }
  div:nth-child(2){
    width: 120px;
    height: 120px;
    background:#998235;
    border-radius:50% 0px 50% 50%;
    margin-top:82px;
    z-index:1
  }
  div:nth-child(3){
    width: 120px;
    height: 120px;
    background:#F3AC3C;
    border-radius:60px 60px 60px 60px;
    margin-top:82px;
    transform:translate(-50%,-50%);
  }
</style>
```

### Ex.6 https://cssbattle.dev/play/6

```html
<div></div>
```
```css
<style>
  body {
    background:#E3516E;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div:nth-child(1){
    width: 200px;
    height: 200px;
    background: conic-gradient(#FADE8B 0% 25%, #E3516E 25% 50%, #F7F3D7 50% 75%, #51B5A9 75% 100%);
    border-radius:50% 50% 50% 50%;
    position: absolute;
  }
</style>
```
