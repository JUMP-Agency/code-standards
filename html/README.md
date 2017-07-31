# HTML Code Style

  1. Accessibility
  2. Attributes
  3. Scripts
  4. Self-Closing Tags
  5. Spacing and Indentation
  6. Validation

### Accessibility

[a11y Style Guide](http://a11y-style-guide.com/style-guide/)

### Attributes

Attributes should be in all lowercase and in order of precendence. Placing the ID first is beneficial since it has the highest specificity. We should never be using ID's for CSS styling, but sometimes it's unavoidable.
  
  1. ID
  2. Class
  3. Name
  4. Data-Attributes
  5. ...

Use double `""` quotes for all attribute values.

correct:
```html
  <div id="js-selector" class="foo" data-bar="true"></div>
```

incorrect:
```html
  <div class='foo' data-bar=true id="js-selector"></div>
```

### Scripts

Omit `type="text/javascript"` from `<script>` elements as they are no longer required in HTML5

correct:
```html
  <script src="./app.js"></script>
```

incorrect:
```html
  <script src="./app.js" type="text/javascript"></script>
```

### Self-Closing Tags

All self-closing tags should have a single space before the closing.

correct:
```html
  <input type="text" />
```

incorrect:
```html
  <input type="text"/>
```

### Spacing and Indentation

  - Spaces instead of tabs
  - Use `2 spaces` for indentation width
  - One element per line

### Validation
