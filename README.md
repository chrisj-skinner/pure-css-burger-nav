# Pure CSS Burger Nav with 100% height background opactity

A simple navigation with a burger nav dropdown appearing on sub 576px. When the navigation is open at this range, a light opacity is applied to the background viewport stretching as far as the body content.

### [DEMO](https://chrisj-skinner.github.io/pure-css-burger-nav/)

## Styling

Applying `overflow-x: hidden;` to the html tag allows up to give the nav menu and exorbitant height. This makes sure the opacity covers all the page content. At the same time we conditionally apply `overflow: hidden;` to the body tag to hide the excess nav content.

![css nav screenshot](./images/screenshot.png 'Screenshot')

Above 576px the navigation is a simple inline format.

## Compatability

Latest(04/20): Edge, Chrome, Firefox, Safari, Opera.
IE 11 upwards.

## MIT License

[https://github.com/chrisj-skinner/pure-css-burger-nav/blob/master/LICENSE](Licence)
