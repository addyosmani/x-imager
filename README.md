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

```
&lt;x-imager availableWidths=&quot;[200, 260, 320, 600]&quot; src=&quot;http://placehold.it/{width}&quot; width=&quot;340&quot;&gt;&lt;/x-imager&gt;
```

```
&lt;x-imager availableWidths=&quot;[400, 460, 420, 1200]&quot; src=&quot;http://placehold.it/{width}&quot; width=&quot;320&quot; class=&quot;img-replace&quot;&gt;&lt;/x-imager&gt;
```

```
&lt;x-imager availableWidths=&quot;[400, 460, 420, 1200]&quot; src=&quot;http://placehold.it/{width}&quot; width=&quot;400&quot; class=&quot;img-replace&quot; resize=&quot;false&quot; className=&quot;imagered&quot; scrollDelay=&quot;100&quot; lazyload=&quot;true&quot;&gt;&lt;/x-imager&gt;
```

