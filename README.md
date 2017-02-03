# QuarterYearPicker
# You can Select quarter and year in q/yyyy format currently, "q1/2017"

Use jquery as a dependency.

# How to use:

Wrap your input field in two div containers as shown:

<div class="qPickerParent">               # this wrapper is must with quarterParent class
	<div class="quarterInput">              # this immediate wrapper is must with quarterInput class
		<input type="text" id="yourFieldId">  # id can be anything
	</div>
</div>

Include the dependencies on your web page.
# Complete flow:

<link href="your path to QuarterYearPicker.min.css" rel="stylesheet">  # Remember to use rel attribute

<div class="qPickerParent">
	<div class="quarterInput">
		<input type="text" id="quarterPicker">
	</div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="your path to QuarterYearPicker.min.js"></script>

