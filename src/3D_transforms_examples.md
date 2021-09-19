# (3D) transforms pavyzdžiai

<style>
.row {
    display: flex;
    justify-content: center;
}

.row--perspective {
    perspective: 200px;
}

.row--origin {
    perspective-origin: left bottom
}

.box {
    box-sizing: border-box;
    width: 150px;
    margin: 0 2em;
    padding: 60px 0;
    text-align: center;
    background-color: hsl(150, 50%, 40%);
}

.box--perspective-rotatex {
    transform: perspective(200px) rotateX(30deg);
}

.box--rotatex {
    transform: rotateX(30deg);
}
</style>

---

<div class="row">
    <div class="box box--perspective-rotatex">One</div>
    <div class="box box--perspective-rotatex">Two</div>
    <div class="box box--perspective-rotatex">Three</div>
    <div class="box box--perspective-rotatex">Four</div>
</div>

```css
.box--perspective-rotatex {
    transform: perspective(200px) rotateX(30deg);
}
```

---

<div class="row row--perspective">
    <div class="box box--rotatex">One</div>
    <div class="box box--rotatex">Two</div>
    <div class="box box--rotatex">Three</div>
    <div class="box box--rotatex">Four</div>
</div>

```css

.row--perspective {
    perspective: 200px
}

.box--rotatex {
    transform: rotateX(30deg);
}
```

---

<div class="row row--perspective row--origin">
    <div class="box box--rotatex">One</div>
    <div class="box box--rotatex">Two</div>
    <div class="box box--rotatex">Three</div>
    <div class="box box--rotatex">Four</div>
</div>

```css
.row--perspective {
    perspective: 200px
}

.row-origin {
    perspective-origin: left bottom
}

.box--rotatex {
    transform: rotateX(30deg);
}
```

---