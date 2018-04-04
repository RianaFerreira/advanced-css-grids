# Advanced CSS - grid

Advanced css exploring the use of grid to build a website.

Browser support https://caniuse.com/#search=grid

Use with FireFox browser for excellent devtools support.

### GETTING STARTED

Install all the npm packages specified in the package.json file.
```
$ npm install
```

Run the server.
The **devserver** script has been configured to launch FireFox as the default browser or optimised CSS grid devtool support.
```
$ npm start
```

Include CSS prefixes automatically and compile the scss into css.
**NB:** won't include prefixes for grid properties.
```
$ npm run build:css
```

### SETUP THE LAYOUT
* Basic HTML markup structure.
* Basic css style per HTML component.
* CSS named grid layout - sidebar with full-bleed sections that are centered in the viewport.
* Differ row and track sizes based on content type.

### FEATURES - NESTING GRIDS
* Responsive components without media queries.
* Small component built with CSS grid.

### STORY - OVERLAPPING GRIDS
* Images vs other grid items.
* Integrating use of Flexbox.

### HOMES - COMBINED CSS layout techniques
* advanced CSS grid properties
* overlapping
* Flexbox

### GALLERY COMPLEX GRID
* `object-fit` with images for grid items

### RESPONSIVE LAYOUT
* media queries

### PROGRESSIVE ENHANCEMENT
* Provide fallback css for older browsers that support CSS grid.
* Feature component example using floats instead.
* Grid and Flexbox ignore: floats, display: inline-block / table-cell, and vertical-align. No need to reset these properties.

### SHORTHAND SYNTAX
* `.gallery` class example for explicitly defining grid rows and columns.

### CSS GRID CONSIDERATIONS
* CSS sub-grids would be useful to snap the nested grid tacks to the parent grids.
* Unable to style specific gaps between cells.
* Missing selectors for nth rows or nth columns.

### REFERENCES
Sass & cheatsheet https://css-tricks.com/the-sass-ampersand/

CSS grid pens:
* auto fit and fill properties https://codepen.io/Riana_Ferreira/pen/LdrJLX
* track min and max properties https://codepen.io/Riana_Ferreira/pen/pLKZQg
* align grid tracks to grid containers https://codepen.io/Riana_Ferreira/pen/Gxxrmb
* align grid items to grid areas https://codepen.io/Riana_Ferreira/pen/EEEZav
* base setup https://codepen.io/Riana_Ferreira/pen/jzzyNP
* named grid areas https://codepen.io/Riana_Ferreira/pen/pLLNxv
* named grid lines https://codepen.io/Riana_Ferreira/pen/VXXmyr
* basic grid layout https://codepen.io/Riana_Ferreira/pen/MVVjMR
* introduction https://codepen.io/Riana_Ferreira/pen/NYYRVB
