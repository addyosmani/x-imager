# &lt;x-imager&gt;

A [Polymer](http://polymer-project.org) element for responsive images with [Imager.js](https://github.com/BBC-News/Imager.js/)

> Maintained by [Addy Osmani](https://github.com/addyosmani).

## Demo

> [Check it live](http://addyosmani.github.io/x-imager/index.html).

## Installation

Install using [Bower](http://bower.io):

```shell
 bower install x-imager
```

## Usage

1. Import Web Components' polyfill (platform.js)

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="x-imager.html">
    ```

3. Start using it!

    ```html
    <x-imager></x-imager>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`src`      | *string*                  | ``                  | URL endpoint for images
`widths`      | *space separated list*                  | ``                  | available image widths
`width`      | *number*                  | ``                  | enforced size of the image placeholder
`selector`      | *string*                  | `delayed-image-load`                  | used to locate your div placeholders
`class`      | *string*                  | ``                  | Class name to give your resizable images
`resize`      | *boolean*                  | `true`                  | update the src attribute of the relevant images
`lazyload`      | *boolean*                  | `false`                  | Toggle the lazy load functionality
`scrollDelay`      | *number*                  | ``                  | helps performance by setting a higher delay


## Examples:

```html
<x-imager widths="200 260 320 600" src="http://placehold.it/{width}" width="340"></x-imager>
```

```html
<x-imager widths="400 460 420 1200" src="http://placehold.it/{width}" width="500" class="img-replace" resize="false" className="imagered"></x-imager>
```

```html
<x-imager widths="400 460 420 1200" src="http://placehold.it/{width}" width="400" class="img-replace" resize="false" className="imagered" scrollDelay="100" lazyload="true"></x-imager>
```

## License

[MIT License](http://opensource.org/licenses/MIT)