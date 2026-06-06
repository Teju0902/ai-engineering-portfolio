# Healthy Recipes

A beginner-friendly CSS project focused on learning and applying different types of CSS selectors to style a recipe webpage.

## Project Overview

This project demonstrates how to use CSS selectors to modify the appearance of an HTML recipe page. The goal is to practice selecting elements by tag name, class, ID, and descendant relationships while improving the visual presentation of the webpage.

## Features Implemented

### 1. Resize Recipe Image

Applied styling to all `img` elements:

```css
img {
  height: 150px;
}
```

### 2. Increase Recipe Description Font Size

Styled the `.description` class:

```css
.description {
  font-size: 20px;
}
```

### 3. Highlight Cooking Time

Used an ID selector for the cooking time section:

```css
#cook-time {
  font-weight: bold;
}
```

### 4. Change Ingredient List Bullets

Targeted list items inside the ingredients section:

```css
.ingredients li {
  list-style: square;
}
```

### 5. Style Preparation Time Text

Selected paragraph elements with the `.time` class:

```css
p.time {
  color: gray;
}
```

### 6. Customize External Recipe Link

Applied a custom color to the recipe source link:

```css
.external-link {
  color: SeaGreen;
}
```

### 7. Change Website Font

Applied Helvetica font to major text elements:

```css
h1,
h2,
p,
li {
  font-family: Helvetica;
}
```

## Technologies Used

* HTML5
* CSS3

## CSS Concepts Practiced

* Element Selectors
* Class Selectors
* ID Selectors
* Descendant Selectors
* Multiple Element Selectors
* Typography Styling
* List Styling
* Color Styling

## Learning Outcomes

By completing this project, I learned how to:

* Select HTML elements using different CSS selector types.
* Apply typography and color styling.
* Modify images and lists with CSS.
* Improve webpage appearance through simple styling techniques.
* Write cleaner and more maintainable CSS code.

## Project Structure

```
healthy-recipes/
│
├── index.html
├── style.css
└── README.md
```

## Author

Created as part of a CSS selectors learning project.
