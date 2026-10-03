# SCSS-style-template

## CSS template for easy project round style manangemt

A complete and highly customisable CSS style template with SCSS. much like bootstrap but easly customisable for your whole project for easy redesign

- **custom variables:** change all the margins, padding and even roundend corner sizes in one place.
- **easy to navigate :** finding which style is where is much easier with proper file naming and highly effiecint code spliting .
- **light weight:** the project itself is very small and easy to intergrate into your own personal project making it a no brainer.
- **Tech Stack:** SCSS.

## Usage

Link to the css file on github or download it and link to it internally

```html
<head>
  <style src="https://github.com/munya-z/scss-style-template/css/styles.css">
</head>
```

use the classes how you would use any normal class in your projects

```html
<section class="bg-light mb-2 pb-4">
    <h1 class="mx-auto t-center fs-medium my-2 clr-primary">This is a heading</h1>
    <p class="">this is a paragraph text</p>
</section>
```

## Customaization

you can customise the variable in the config-variables folder.

```scss
$colors:(
    primary:hsl(226, 100%, 50%),
    secondary:hsl(150, 100%, 50%),
    // you can your more colors if required, the helper 
    // classes will automatical be added
    link:rgb(195, 0, 255),
    dark: rgb(19, 19, 19),
    light:rgb(239, 239, 239)
);

// these are the shades break points which you can also change to suit your needs 
$color-shades:(
    80:80%,
    60:60%,
    40:40%,
    20:20%
);
```

the variable are spilt into separate files depending on what they do for easy access and ease of editing.

### Feel free to fork the project and create your own template for your person taste.
