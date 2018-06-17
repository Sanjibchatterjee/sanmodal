# sanmodal
Free Responsive Modal
For using in your html, PHP, .Net, Java, Python, NodeJs project.

Free for use for the purpose of personal and commercial till you keep the copyright information in header as it is.
### Example: [San Modal](http://sanjibchatterjee.com/sanmodal/sanmodal.html).

## How to use?
* Link the CSS file sanmodal.css with the html
* Add the following html-
```
<div id="sanmodal" class="sanmodal">
	<div class="modal-wrapper">
		<div class="modal-top">
			<span class="close" id="close">&times;</span>
			<div class="modal-title">Modal 1 Title</div>
		</div>

		<div class="modal-contents">
			Modal subjects and data goes here. . . .<br>
			More data goes here. . . .<br>
			And more data goes here. . . .<br>
		</div>
		<div class="modal-bottom">Modal bottom part.</div>
	</div>
</div>
```
* Add the following javascript in the html after the related html code, ie at bottom part inside the body
```
<script>
var modal = document.getElementById('sanmodal');
var btn = document.getElementById('openBtn');
var close = document.getElementById('close');
</script>
```
* Link the Javascript file sanmodal.js under the above script. and Bingo!
