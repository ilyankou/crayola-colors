# crayola-colors 1.0
List of 186 Crayola crayon colors for the web

* 186 colors
* 930 selectors
* 35.9 KB

## Installation
Download the .css file and add it to your project folder.

In the head of your HTML file, add:
```
<link rel="stylesheet" href="path/to/crayola-colors.css">
```

## Usage
For colors, `.cr-color-name`:
```
<div class=".cr-asparagus">Hello, World!</div>
```

For background colors, `.cr-bg-color-name`:
```
<div class=".cr-maximum-green">Hello, World!</div>
```

For border colors, `.cr-border-color-name`:
```
<div class=".cr-border-maize">Hello, World!</div>
```

For SVG fill and stroke colors, `.cr-fill-color-name` and `.cr-stroke-color-name`, respectively:
```
<svg width="160" height="280" xmlns="http://www.w3.org/2000/svg" version="1.1">
  <polyline points="40 60 80 20 120 60" class=".cr-stroke-gold .cr-fill-sepia" stroke-width="20"
      stroke-linecap="butt" stroke-linejoin="miter"/>
</svg>
 ```

## License
The MIT License
