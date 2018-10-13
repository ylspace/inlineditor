# inlineditor
Inlineditor is a WYSIWYG editor for web pages. Its goal is to be powerful and simple and configurable. Inlineditor is extremely lightweight and can be easily integrated in any web application.


## features
- Extremely lightweight
- Multilingual
- Configurable
- Themes


## Dependencies
inlineditor has some very common dependencies shown below
- jquery
- font-awesome


## Usage

#### Add belowe lines to your html page
```
<script type="text/javascript" src="jquery.js"></script>
<link rel="stylesheet" type="text/css"  href="font-awesome.min.css" />

<script type="text/javascript" src="dist/js/inlineditor.js"></script>
<link rel="stylesheet" type="text/css"  href="dist/css/inlineditor.css" />
```

#### HTML
```
<div id="container"></div>
```

#### Javascript
```
var editor = $.inlineditor('div#container', {
  /*options*/
  ...
});
```

### Demos
- Basic (https://mjahmadi.github.io/inlineditor/demos/basic.html)
- Editors (https://mjahmadi.github.io/inlineditor/demos/editors.html)
- Full featured (https://mjahmadi.github.io/inlineditor/demos/full.html)