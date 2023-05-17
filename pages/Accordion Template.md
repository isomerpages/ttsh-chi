---
title: Accordion Template
permalink: /accordion/
description: ""
---
<style>

input {
	display: none;
}
label {
	display: block;
	padding: 8px 22px;
	margin: 0 0 5px 0;
	cursor: pointor;
	background: #F0F4F6; *colour*
	border-radius: 3px;
	color: #484848; *colour of text*
	transition: ease .5s;
	font-size: 1.5em;
}

label:hover {
	background: #4a96b0;
	color: ##D1C052;
}

.accordion-content {
	/* background: ##D1C052; */
	padding: 10px 0px 30px 30px;
	/* border: 1px solid #484848; */
	margin: 0 0 1px 0;
	border-radius: 3px;
}

input + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: block;
}

</style>
<!-- End of accordion -->

<div class="container">

<h1><b>Accordian Table Template</b></h1>

<p><strong>HEader Text </strong><br>  Sample text Sample text Sample text Sample text Sample text Sample text Sample text Sample text Sample textSample textSample text Sample text  .</p>
	
<p><strong>Header 2</strong><br>  Sample text Sample text Sample textSample textSample textSample textSample text.</p>
<p><strong>Header 3</strong><br>  Sample text Sample text Sample text Sample text Sample text Sample text Sample text Sample text.</p>

<h2 id="our-main-plans">Accordian Table Heading Text</h2>
<div>
	<input id="title1" type="checkbox"><label for="title1">Tab 1</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text.</p>
	</div>
	<input id="title2" type="checkbox"><label for="title2">Tab 2</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text.</p>
	</div>
	<input id="title3" type="checkbox"><label for="title3">Tab 3</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text. Sample text Sample text Sample text Sample text Sample text Sample text Sample text. .</p>
	</div>
	<input id="title4" type="checkbox"><label for="title4">Tab 4</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text..</p>
	</div>
	<input id="title5" type="checkbox"><label for="title5">Tab 5</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text..</p>
	</div>
</div>

	
	
<a id="If another Accordian Table is needed"></a>

<h2>If another Accordian Table is needed</h2>
<div>
	<input id="title6" type="checkbox"><label for="title6">Title 1 with Picture</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text
			</p>
	</div>
	<input id="title7" type="checkbox"><label for="title7">Title 2</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text.</p>
	</div>
	<input id="title8" type="checkbox"><label for="title8">Title 3</label>
	<div class="accordion-content">
		<p>Sample text Sample text Sample text Sample text Sample text Sample text Sample text.</p>
	</div>
</div>

	
<a id="If a 3rd Table is needed"></a>

<h2>If a 3rd Table is needed</h2>
<div>
	<input id="title9" type="checkbox"><label for="title9">Title 4</label>
	<div class="accordion-content">
		<p>Text Text Text.</p>
	</div>
	<input id="title10" type="checkbox"><label for="title10">Title 5</label>
	<div class="accordion-content">
		<p>Text Text Text with Paragraph</p>
		<p>A second Paragraph.</p>
		<p>And a Third One.</p>
	</div>
</div>



</div>

Therefore for example,