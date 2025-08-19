# St James's Church, Biddenham WordPress SCSS

![St James's Church logo](assets/images/st-james-church-logo-black.webp)

This folder contains the SCSS and CSS files used on the stjames child theme for the St James's Church website.

The St James's Church website uses the free version of the [Astra](https://wpastra.com/) parent theme.

## How to use

Form this folder, run one of these scripts:

To generate a compressed version of the CSS (preferred) which watches as changes are made

`sass --watch ./scss/style.scss:./css/style.css --no-source-map --style=compressed`

To generate an uncompressed version of the CSS (for testing) which watches as changes are made:

`sass --watch ./scss/style.scss:./css/compiled_custom_style.css --no-source-map --style=expanded`

As a one-off CSS generation script, run this:

`sass ./scss/style.scss ./css/style.css --no-source-map --style=compressed`

or this:

`sass ./scss/style.scss ./css/style.css --no-source-map --style=expanded`

## Installation

This uses the Dart Sass command-line interface (CLI), which is part of the sass npm package.

To install this globally:

`npm install -g sass`
