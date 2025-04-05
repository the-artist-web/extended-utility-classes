# Extended Utility Classes for Bootstrap

This CSS file provides an extensive set of utility classes designed to complement and extend the default utility classes provided by Bootstrap. It includes comprehensive padding, margin, width, height, and responsive media query utilities, all with `!important` applied for higher specificity.

## Features

### Padding Classes
- `.p-{value}`: Applies padding to all sides.
- `.pt-{value}`: Applies padding to the top.
- `.pb-{value}`: Applies padding to the bottom.
- `.pl-{value}`: Applies padding to the left.
- `.pr-{value}`: Applies padding to the right.
- `.px-{value}`: Applies padding to the left and right.
- `.py-{value}`: Applies padding to the top and bottom.

### Margin Classes
- `.m-{value}`: Applies margin to all sides.
- `.mt-{value}`: Applies margin to the top.
- `.mb-{value}`: Applies margin to the bottom.
- `.ml-{value}`: Applies margin to the left.
- `.mr-{value}`: Applies margin to the right.
- `.mx-{value}`: Applies margin to the left and right.
- `.my-{value}`: Applies margin to the top and bottom.

### Width and Height Classes
- `.w-auto`: Sets the width to auto.
- `.w-full`: Sets the width to 100%.
- `.w-{value}px`: Sets the width to `{value}` pixels.
- `.max-w-{value}px`: Sets the max-width to `{value}` pixels.- 
- `.min-w-{value}px`: Sets the min-width to `{value}` pixels.
- `.h-auto`: Sets the height to auto.
- `.h-full`: Sets the height to 100%.
- `.h-{value}px`: Sets the height to `{value}` pixels.
- `.max-h-{value}px`: Sets the max-height to `{value}` pixels.- 
- `.min-h-{value}px`: Sets the min-height to `{value}` pixels.

### Responsive Media Queries
Classes are available for different screen sizes using the following breakpoints:
- `sm`: Screens up to 576px.
- `md`: Screens up to 768px.
- `lg`: Screens up to 992px.
- `xl`: Screens up to 1200px.

#### Example:
- `.p-sm-{value}`: Padding for small screens.
- `.p-md-{value}`: Padding for medium screens.
- `.p-lg-{value}`: Padding for large screens.
- `.p-xl-{value}`: Padding for extra-large screens.

### Bootstrap Compatibility
This file is designed to be used alongside Bootstrap, extending its functionality while maintaining its structure and naming conventions. All classes are compatible and work seamlessly with Bootstrap's default classes.

## How to Use
1. Link the CSS file to your project after including Bootstrap:
   ```html
   <link rel="stylesheet" href="bootstrap.min.css">
   <link rel="stylesheet" href="extended-utility-classes.min.css">
   ```
2. Use the classes in your HTML as needed, just like you would with Bootstrap.

#### Example Usage:
```html
<div class="p-50 m-20 w-300px h-200px p-md-30">
  Content goes here
</div>
```