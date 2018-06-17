# sanmodal
Free Responsive Modal
For using in your HTML, PHP, .Net, Java, Python, NodeJs, Ruby, Angular, React projects.

Free for use for the purpose of personal and commercial till you keep the copyright information in header as it is.
### Example: [San Modal](http://sanjibchatterjee.com/sanmodal/sanmodal.html).

## How to use?
* Link the CSS file sanmodal.css with the html inside <head> Tag.
* Link the button/ div/ image/ any element, you like to link the modal with as per given Id.
```
<div id="openBtn">Modal 1</div>
```
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
* Add the following javascript in the html after the related html code, ie at bottom part inside the body. This is the custom part where you can change the id as per the id given to the element.
```
<script>
var modal = document.getElementById('sanmodal');
var btn = document.getElementById('openBtn');
var close = document.getElementById('close');
</script>
```
* Link the Javascript file sanmodal.js under the above script. and Bingo!
## NB: There is more in this plugin-
If you like to have the modal pop up from downside and stays at bottom you just need to change the id and class as per following information:
The js- 
```
var modalbot = document.getElementById('sanmodalbot');
var btnbot = document.getElementById('openBtnbot');
var closebot = document.getElementById('closebot');
```
and just change the id & class names from sanmodal to sanmodalbot; modal-wrapper to modal-wrapperbot in the html. And your modal will be coming from bottom like you see in mobiles.


