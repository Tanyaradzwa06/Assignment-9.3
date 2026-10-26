## Assignment 9.3 — COMBINE FLEXBOX AND GRID RESPONSIVELY

Title: Combine Flexbox and Grid Responsively

### 1. Introduction

CSS Grid and CSS Flexbox are modern CSS layout techniques used to create responsive and attractive web pages. CSS Grid is mainly used for two-dimensional layouts, while Flexbox is used for one-dimensional layouts. By combining both techniques, we can create websites that adapt to different screen sizes, such as desktops, tablets, and mobile phones.

### 2. What is CSS Flexbox?

CSS Flexbox (Flexible Box Layout) is a CSS layout model used to arrange elements in a row or column. It helps align items, distribute space, and create flexible layouts.

Advantages of Flexbox:

- Aligns elements horizontally and vertically.
- Distributes space between items.
- Makes navigation bars easy to design.
- Helps create flexible and responsive layouts.

Example:

css

```
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

### 3. What is CSS Grid?

CSS Grid is a two-dimensional CSS layout system used to arrange elements in rows and columns. It is useful for designing complete page layouts, image galleries, and card sections.

Advantages of CSS Grid:

- Creates rows and columns easily.
- Organizes content into structured layouts.
- Provides control over spacing and alignment.
- Supports responsive designs using media queries.

Example:

css

```
.feature-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}
```

### 4. Difference Between Flexbox and Grid

| CSS Flexbox | CSS Grid |
| --- | --- |
| One-dimensional layout system. | Two-dimensional layout system. |
| Works mainly with rows or columns. | Works with rows and columns together. |
| Suitable for navigation bars and buttons. | Suitable for page layouts and card grids. |
| Distributes items along one main axis. | Controls layout across two axes. |

### 5. What is Responsive Web Design?

Responsive web design is an approach to web development that allows a website to adjust automatically to different screen sizes and devices. It uses flexible layouts, responsive images, and CSS media queries to improve usability.

Example:

css

```
@media (max-width: 600px) {
    .feature-grid {
        grid-template-columns: 1fr;
    }
}
```

This code changes the feature section to a single column when the screen width is 600 pixels or less.

### 6. Combining Flexbox and Grid

In this assignment, CSS Grid and Flexbox are used together to create a responsive landing page.

- Header and navigation bar: Flexbox aligns the logo, navigation links, and button.
- Hero section: Grid arranges the text and image in two columns.
- Features section: Grid arranges three to six feature cards in rows and columns.
- Card content: Flexbox arranges icons, headings, and descriptions vertically.
- Mobile layout: Media queries change multiple columns into a single column.

### 7. Advantages of Combining Flexbox and Grid

1. Creates clean and organized layouts.
2. Improves website responsiveness.
3. Provides better control over spacing and alignment.
4. Reduces the need for complicated positioning.
5. Makes websites easier to maintain.
6. Improves the user experience across different devices.

### 8. Conclusion

CSS Grid and Flexbox are powerful layout techniques in modern web development. Flexbox is useful for aligning elements in one direction, whereas Grid is suitable for arranging content in rows and columns. Combining these techniques with media queries helps create responsive, user-friendly, and visually appealing websites that work well on desktops, tablets, and mobile devices.

## Complete responsive page checking spacing and alignment

![alt text](<mobile image.png>)
![alt text](<desktop image.png>)
## Desktop screenshot
![alt text](<desktop screenshot.png>)
## Mobile Screenshot
![alt text](<mobile screenshot.png>)
