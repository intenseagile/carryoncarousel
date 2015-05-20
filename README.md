# Carry On Carousel

Carry on Carousel is a minimal jQuery based image carousel/image slider.

## Anti-features

* No configuration options
* No keyboard control
* No pause and play
* Forward only 

## Rationalle

Carousel's are a dime a dozen. Carousels also offer so many options that just setting one up can often take more time than simply rolling your own.

Carry on Carousel is designed to be a set and forget image carousel. There are no options. It runs at one speed, supports one transition and has only one way to define your images - through data-attributes.

# How To

## 1) Install

* Download the .js file and put it in your ```/js``` directory.
* Reference the .js file in your html page/template.

## 2) Set up your carousel container

You'll need an html element to hold your carousel. You'll probably wan this to be full width, absolutely positioned and sitting behind everything else on your page. 

Using the ```data-images``` data attribute on your element, specify the array of images you want to display in your carousel.

For example, assuming an images folder called ```img```, your html would look like this:

```html
<div id="carousel"  data-images='["img/white.jpg", 
                                  "img/yellow.jpg", 
                                  "img/amazing.jpg", 
                                  "img/street.jpg"]'>
</div>
```
## 3) Activate the plugin

Call the plugin on the jQuery load:

```html
<script>
    $(function() {
        $("#carousel").carryOnCarousel();                
    });
</script>
```

## 4) Enjoy


# Example

There's an example in the repo's ```example``` folder, complete with some minimal styling based on (Bootstrap)(http://getbootstrap.com).

jQuery plugin based image carousel/image slider. Data attribute driven.
