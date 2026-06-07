# Challenges and Solutions

## Challenge 1: Fixed Header Positioning

### Problem

The header moved with the rest of the page during scrolling.

### Solution

```css id="ab12cd"
header {
  position: fixed;
}
```

### Lesson Learned

Fixed positioning keeps important navigation visible at all times.

---

## Challenge 2: Header Width Shrinking

### Problem

After applying fixed positioning, the header no longer stretched across the page.

### Solution

```css id="ef34gh"
header {
  width: 100%;
}
```

### Lesson Learned

Fixed elements often require explicit width declarations.

---

## Challenge 3: Horizontal Navigation Layout

### Problem

Navigation links appeared vertically as a traditional list.

### Solution

```css id="ij56kl"
nav li {
  display: inline-block;
}
```

### Lesson Learned

Inline-block combines horizontal flow with block-level sizing capabilities.

---

## Challenge 4: Overlapping Content

### Problem

The fixed header covered portions of the page content.

### Solution

```css id="mn78op"
main {
  position: relative;
  top: 80px;
}
```

### Lesson Learned

Position offsets help create space for fixed elements.

---

## Challenge 5: Stacking Order Issues

### Problem

The header disappeared behind the main content.

### Solution

```css id="qr90st"
header {
  z-index: 5;
}
```

### Lesson Learned

Z-index determines which elements appear in front when overlap occurs.

---

## Challenge 6: Supporting Sections Not Aligning

### Problem

The Design, Develop, and Deploy sections remained stacked vertically.

### Solution

```css id="uv12wx"
.supporting .col {
  display: inline-block;
}
```

### Lesson Learned

Elements need appropriate display properties before horizontal alignment can occur.

---

## Challenge 7: Column Sizing

### Problem

Columns did not align properly because they lacked dimensions.

### Solution

```css id="yz34ab"
.supporting .col {
  width: 200px;
  height: 200px;
}
```

### Lesson Learned

Defining dimensions creates consistency and improves layout control.

---

## Key Takeaways

This project strengthened understanding of:

* Fixed positioning
* Relative positioning
* Display properties
* Z-index layering
* Horizontal layouts
* Navigation design

These concepts form the foundation of modern webpage layout development.

## Reflection

The Broadway Design project demonstrated how a few CSS properties can dramatically improve usability and visual structure. Understanding how positioning and display interact is essential for building responsive and professional web interfaces.
