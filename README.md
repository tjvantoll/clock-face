# Clock Face

A web component for building clocks, inspired by the clock that appears on [Moment.js' home page](http://momentjs.com/).

<img src="http://i.imgur.com/zbP1ode.png" alt="clock face">

### Live Demo

[Here you go](http://jsfiddle.net/tj_vantoll/gnf2j/).

### Usage

Include the component's JS/CSS, and then use the `<clock-face>` element.

```
<link rel="stylesheet" href="clock-face.css">
<script src="clock-face.js"></script>

<clock-face></clock-face>
```

The `<clock-face>` element displays the current time by default. You can alternatively display a static time using the `hour`, `minute`, and `second` attributes.

```
<clock-face hour="9" minute="30" second="10"></clock-face>
```

### Dependencies

The component requires a custom elements polyfill, either [Polymer's](https://github.com/Polymer/CustomElements) or [Andrea Giammarchi's](https://github.com/WebReflection/document-register-element); I recommend the latter, as it's lightweight and does everything the `<clock-face>` element needs. 

### Browser Support

* IE 9+
* Firefox
* Chrome
* Safari
* Opera
* iOS Safari
* Android Browser
* Chrome for Android

IE versions < 9 are not supported because the component relies on CSS transformations.
