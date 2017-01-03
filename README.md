# jQuery Typing Machine Script

Usage
-----

```html
<script src="jTyping/js/jTyping.min.js"></script>
<link rel="stylesheet" type="text/css" href="jTyping/css/jTyping.css">
```

Examples
--------
```html
<div class="terminal typingCursor">-- You are visiting norfolky.com --</div>
```

Tutorial
--------
```javascript
$(document).ready( function(){
	setTimeout( function(){
		$('.terminal').typewriting($('.terminal').text(),
			{
			"typing_interval": 150,
			"blink_interval": "1s",
			"cursor_color": "#00fd55"
		}, function() {
			console.log("END");
		});
	}, 1000);
});
```
