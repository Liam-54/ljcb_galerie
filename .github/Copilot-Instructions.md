# CSS/HTML Learning Guide

## Basic CSS Concepts (LZ1-LZ10)

### CSS Selectors (LZ2-LZ3)
- **Tag Selector**: Targets HTML elements directly
  ```css
  p { color: blue; }
  ```
- **Class Selector**: Targets elements with specific class
  ```css
  .highlight { background-color: yellow; }
  ```
- **ID Selector**: Targets specific unique element
  ```css
  #header { font-size: 24px; }
  ```

### Text Formatting (LZ4)
```css
h1 {
    color: #333;
    font-size: 2em;
    font-family: Arial, sans-serif;
}
```

### CSS Integration Methods (LZ5-LZ6)
1. External CSS file:
```html
<link rel="stylesheet" href="styles.css">
```
2. Internal CSS:
```html
<style>
    /* CSS rules here */
</style>
```

### CSS Comments and Standards (LZ7-LZ9)
```css
/* This is a proper CSS comment */
/* Use consistent indentation and spacing */
.example {
    /* Property group for typography */
    font-size: 16px;
    line-height: 1.5;
}
```

## Layout and Positioning (LZ11-LZ18)

### Margin vs Padding (LZ11)
- Margin: Space outside element
- Padding: Space inside element

### Positioning (LZ13-LZ15)
```css
/* Relative positioning */
.relative {
    position: relative;
    top: 10px;
}

/* Absolute positioning */
.absolute {
    position: absolute;
    top: 0;
    left: 0;
}

/* Fixed positioning */
.fixed {
    position: fixed;
    bottom: 0;
}
```

## Responsive Design (LZ20-LZ28)

### Grid System (LZ20-LZ21)
- 12-column grid provides flexible layout options
```css
.grid {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
}
```

### Media Queries (LZ23-LZ25)
```css
/* Example breakpoint */
@media screen and (max-width: 768px) {
    .container {
        width: 100%;
    }
}
```

## Bootstrap Framework (LZ29-LZ34)
```html
<!-- Bootstrap setup -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.x.x/dist/css/bootstrap.min.css" rel="stylesheet">
```

### Responsive Grid
```html
<div class="container">
    <div class="row">
        <div class="col-12 col-md-6 col-lg-4">Content</div>
    </div>
</div>
```

## Multimedia and Animation (LZ35-LZ37)
```html
<!-- Responsive image -->
<img class="img-fluid" src="image.jpg" alt="Description">

<!-- YouTube embed -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
```

## Testing (LZ38-LZ41)
1. Cross-browser testing checklist:
   - Chrome
   - Firefox
   - Safari
   - Edge

2. Test documentation template:
```markdown
| Test Case | Expected Result | Actual Result | Status |
|-----------|----------------|---------------|---------|
| Mobile view | Menu collapses | Menu collapses | ✅ |
```

### ISO 9241-110 Criteria (LZ19)
1. Suitability for the task
2. Self-descriptiveness
3. Conformity with user expectations
4. Suitability for learning
5. Controllability
6. Error tolerance
7. Suitability for individualization

### CSS Validation (LZ8)
Use W3C CSS Validator: https://jigsaw.w3.org/css-validator/
