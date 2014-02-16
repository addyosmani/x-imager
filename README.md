x-imager
========

A Polymer responsive images element using Imager.js

Supported attributes:

* src 
* availableWidths
* width 
* selector 
* class 
* resize 
* lazyload 
* scrollDelay

Examples:

```html
<x-imager availableWidths="[200, 260, 320, 600]" src="http://placehold.it/{width}" width="340"></x-imager>
```

```html
<x-imager availableWidths="[400, 460, 420, 1200]" src="http://placehold.it/{width}" width="500" class="img-replace" resize="false" className="imagered"></x-imager>
```

```html
<x-imager availableWidths="[400, 460, 420, 1200]" src="http://placehold.it/{width}" width="400" class="img-replace" resize="false" className="imagered" scrollDelay="100" lazyload="true"></x-imager>
```

