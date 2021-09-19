# Transition pavyzdis

---

<style>
    button {
        background-color: hsl(180, 50%, 50%);
        border: 0;
        color: white;
        font-size: 16px;
        padding: 2px 16px;
        transition-property: all;
        transition-duration: 0.5s;
    }

    button:hover {
        background-color: hsl(0, 50%, 50%);
        border-radius: 15px;
    }
</style>

<button>Hover over me</button>

---

```html
<button>Hover over me</button>
```

```css
    button {
        background-color: hsl(180, 50%, 50%);
        border: 0;
        color: white;
        font-size: 16px;
        padding: 2px 16px;
        transition-property: all;
        transition-duration: 0.5s;
    }

    button:hover {
        background-color: hsl(0, 50%, 50%);
        border-radius: 5px;
    }
```