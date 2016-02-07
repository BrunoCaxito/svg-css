# svg-css
A simple custom element in polymer, allowing SVG images to be styled with CSS in HTML pages.

## Using

Add Polymer to your page.

    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>

Import the element.

    <link rel="import" href="bower_components/svg-css/svg-css.html">

Use the element where you want just like an inline img.

    <svg-css src="demo.svg"></svg-css>

Style it free.

    <style>
        path {
            fill: red;
        }
    </style>

## Bower Install

You can also install using the Bower repo:

    bower install --save svg-css

## License

Everything in this repository is MIT style license.

Copyright (c) 2016 Bruno Caxito. All rights reserved.
