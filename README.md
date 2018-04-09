# jQuery Nice Select

A lightweight jQuery plugin that replaces native select elements with customizable dropdowns.

## Usage

Include jQuery and the plugin.

```html
<script src="path/to/jquery.js"></script> 
<script src="path/to/jquery.nice-select.js"></script>
```

Include the plugin styles, either the compiled CSS...

```html
<link rel="stylesheet" href="path/to/nice-select.css">
```

...or, ideally, import the SASS source (if you use SASS) in your main stylesheet for easier customization.

```scss
@import 'nice-select';
```

Finally, initialize the plugin.

```javascript
$(document).ready(function() {
  $('select').niceSelect();
});
```

For Custom Layout

```javascript
$(document).ready(function() {
  $('select').niceSelect({
    customLayout: true
  }); 
});
```

Full documentation and examples at [hernansartorio.com/jquery-nice-select](http://hernansartorio.com/jquery-nice-select).
