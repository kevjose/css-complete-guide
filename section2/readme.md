# Section 2

### Adding style to HTML

- inline style using style attribute `style="background: red"`, here background is a property, style the background to a value, inline styles are not recommended

- styling using selectors, either using style tag or a .css file (external stylesheet)

```css
<style>
  /* apply below style to all section tags on the page */
  section {
    background: #ff1b68;
  }
</style>
```

```html
<!-- using external css files , the recommended way-->
<link rel="stylesheet" href="main.css" />
```

### Adding more styles

```css
section {
  background: #ff1b68;
}

h1 {
  color: white;
  font-family: sans-serif; /* this is browser default, also used as a fallback */
}
```

- using external font family

```html
<link
  href="https://fonts.googleapis.com/css?family=Anton&display=swap"
  rel="stylesheet"
/>
```

```css
section {
  background: #ff1b68;
}

h1 {
  color: white;
  font-family: 'Anton', sans-serif;
}
```

### Different styles for different sections
