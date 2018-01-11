Jquery Menu Click Image Swap
===============================
## Demo Link
	http://techansh.com/git-projects/jqMenuClick/index.html

## Usage

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="js/jqMenuClick.js"></script>
	```
3. Keep the news data div and list of news in html
	
	```html
	<h3 id="aboutMenuMobile"> About <span class="glyphicon glyphicon-chevron-down" ></span></h5>
	```
	
4. Call the plugin:

	```javascript
	$(function () {
		$('#aboutMenuMobile').menuClick({
			// set values and custom functions
			menuExpandedClass:"glyphicon glyphicon-chevron-up",
			menuCollapseClass:"glyphicon glyphicon-chevron-down",
		});
	});
	```
	
## Issues:
	Please file issues on Github : https://github.com/jayeshmagare/jqMenuClick/issues
	
## License

	MIT License http://opensource.org/licenses/MIT	

Copyright 2014 Jayesh Magare
