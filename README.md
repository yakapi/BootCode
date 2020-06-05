# BootCode
Quelque Code utile

## Input Custom
#html
```html
<form class="" action="index.html" method="post">
  <div class="cusput">
    <input class="custom-input" type="text" name="" value="" placeholder="rechercher">
    <div class="encard-glass">
      <img src="search.svg" alt="">
    </div>
  </div>
</form>
```
#css
```css
.custom-input{
  border: 1px solid royalblue;
  background-color: royalblue;
}
.custom-input:focus{
  outline: 0;
}
.custom-input::placeholder{
  color: yellow;
  font-weight: bold;
}
/* Supplément */
.cusput{
  background-color: royalblue;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 28px;
  width: 210px;
  border-radius: 5px;
}
.encard-glass{
  width: 20px;
  height: 20px;
}
.encard-glass img{
  width: 100%;
  height: 100%;
}

```
## Object fit
#html
```html
<div class="encard-logo">
  <img class="fit" src="chanel.png" alt="">
</div>
<div class="encard-logo">
  <img class="fit" src="fila.png" alt="">
</div>
```
#css
```css
.fit{
  object-fit: contain;
}
.encard-logo{
  width: 120px;
  height: 120px;
}
.encard-logo img{
  width: 100%;
  height: 100%;
}
```
