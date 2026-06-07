# Broadway Design - Display and Position Project

## Overview

This project focuses on improving the layout of the Broadway Design landing page using CSS positioning and display properties.

The objective is to transform a basic webpage into a more polished and professional design by implementing fixed navigation, horizontal layouts, proper spacing, and layered positioning.

## Learning Objectives

Through this project, you will learn how to:

* Use CSS positioning properties
* Create fixed navigation bars
* Control stacking order with z-index
* Offset elements using relative positioning
* Arrange content horizontally with display properties
* Build structured page layouts

## Technologies Used

* HTML5
* CSS3

## Features Implemented

### Fixed Header Navigation

The header was configured to remain visible at the top of the page while scrolling.

```css id="1l2m3n"
header {
  position: fixed;
  width: 100%;
}
```

### Horizontal Navigation Menu

Navigation links were converted from a vertical list into a horizontal menu.

```css id="4o5p6q"
nav li {
  display: inline-block;
  width: 80px;
}
```

### Relative Main Content Positioning

The main content was repositioned to account for the fixed header.

```css id="7r8s9t"
main {
  position: relative;
  top: 80px;
}
```

### Layer Management with z-index

The header was placed above page content.

```css id="0u1v2w"
header {
  z-index: 5;
}
```

### Supporting Columns Layout

The Design, Develop, and Deploy sections were aligned horizontally.

```css id="3x4y5z"
.supporting .col {
  display: inline-block;
  width: 200px;
  height: 200px;
}
```

## CSS Concepts Practiced

### Position: Fixed

Keeps an element attached to the viewport regardless of scrolling.

### Position: Relative

Allows elements to be shifted from their normal position.

### Display: Inline-Block

Places elements side-by-side while preserving width and height properties.

### Z-Index

Controls the stacking order of overlapping elements.

## Project Outcome

After completing the project:

* The navigation remains accessible while scrolling.
* Page sections align more effectively.
* The layout appears more organized and professional.
* Supporting content displays in a clean horizontal arrangement.

## Possible Enhancements

* Create a fixed footer.
* Add hover effects to navigation links.
* Improve responsiveness with media queries.
* Add CSS transitions and animations.

## Author

Completed as part of a CSS Layout and Positioning practice project.
