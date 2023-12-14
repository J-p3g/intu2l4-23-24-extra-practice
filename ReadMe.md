# CSS Selector Review

## Key Concepts

### Class Attributes
- **Definition**: Class attributes enable you to apply styles to specific HTML elements, rather than all elements of the same type.
- **Syntax**: `<tag class="classname">content</tag>`
- **CSS Selector**: To apply styles, use a period before the class name in your CSS file: 
  ```css
  .classname { property: value; }
  ```
  - **REMEMBER**: Use a period in front of a class selector. No period is needed to style a tag selector (ex. h1, img, div, etc.).

### Steps to Using Class Attributes
1. **HTML**: Decide which tags to style differently and add a class attribute with a meaningful name.
2. **CSS**: Write the styling rules using the class selector.
3. **Example**: 
  ```html
  <p class="highlight">Important text</p>
  ```
  ```css
  .highlight { background-color: yellow; }
  ```

## Error Spotting
- **Case Sensitivity**: Class names are case-sensitive; make sure to match the exact case in both HTML and CSS.

<br>

Happy coding!