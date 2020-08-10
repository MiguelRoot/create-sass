# Config Grid
> Grid based customizable grid. [documentation](https://miguelroot.github.io/displayflex/)


## Install:

### npm
``npm i create-sass``

### import
```
@import "node_modules/create-sass/create-sass";
```
## config
```
$unit: .5rem !default;
$dev: true !default;
$columns: 12 !default;
$container-gap: 0 $unit*2 $unit*5 !default;
$col-gap: 0 $unit*2 30px !default;

$breakpoints: (
    "xs": 0,
    "sm": 769px,
    "md": 1024px,
    "lg": 1216px,
    "xl": 1408px,
);
```