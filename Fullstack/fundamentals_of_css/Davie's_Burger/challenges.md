# Challenges and Solutions

## Challenge 1: Centering Elements Horizontally

### Problem

The logo image and several block-level elements needed to be centered.

### Solution

Used automatic left and right margins.

```css
margin: 0 auto;
```

### What I Learned

Auto margins center block elements when a width is defined.

---

## Challenge 2: Understanding Margin vs Padding

### Problem

It was initially unclear whether spacing should be added inside or outside an element.

### Solution

* Used **padding** for internal spacing.
* Used **margin** for external spacing.

### What I Learned

Padding increases space inside the border, while margin separates elements from each other.

---

## Challenge 3: Content Overflow

### Problem

The content section exceeded its fixed height when the browser window became narrow.

### Solution

```css
overflow: scroll;
```

### What I Learned

The overflow property controls how excess content is displayed.

---

## Challenge 4: Styling the Button

### Problem

The button appeared too small and lacked visual emphasis.

### Solution

```css
width: 200px;
padding: 20px;
border: 1px solid blue;
margin: 40px auto;
```

### What I Learned

Combining width, padding, border, and margin creates a more professional button design.

---

## Challenge 5: Working with Nested Selectors

### Problem

Some styles only needed to affect elements inside specific containers.

### Solution

```css
.header h1
.content .body
ul.nutrition li
```

### What I Learned

Nested selectors help target elements precisely without affecting the rest of the page.

---

## Challenge 6: Building a Consistent Layout

### Problem

Different sections looked disconnected due to inconsistent spacing.

### Solution

Applied consistent margin and padding values throughout the page.

### What I Learned

Consistent spacing is essential for creating visually balanced layouts.

---

## Reflection

This lab reinforced the importance of the CSS Box Model and demonstrated how width, height, padding, border, margin, and overflow work together to control webpage layout and presentation.
