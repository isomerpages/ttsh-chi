---
title: Accordion Template
permalink: /permalink/
description: ""
---
<style>
.button {
  background-color: white;
  cursor: pointer;
  padding: 5px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
  transition: 0.4s;
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: white;
  overflow: hidden;
}

img {
  width: 150px;
  height: 180px;
}

.active,
.button:hover {
  background-color: white;
}

input {
  display: none;
}

label {
  position: relative;
  display: block;
  padding: 8px 22px;
  margin: 0 0 5px 0;
  cursor: pointer;
  background: #F0F4F6;
  border-radius: 3px;
  width: 100%;
  color: #484848;
  transition: height 0.4s;
  font-size: 1.5em;
}

label:hover {
  background: #BD2D37;
  color: #FFF;
}

.accordion-content {
  padding: 10px 0px 30px 30px;
  margin: 0 0 1px 0;
  border-radius: 3px;
	font-size: 1.25em;
	line-height: 2.2rem;
}

input + label::before {
  content: url("https://d33wubrfki0l68.cloudfront.net/2726d99e678e7823e23532634fdd6e83dfe96a99/c39dd/images/chevron-down.svg");
  font-weight: 400;
  font-size: 1.25em;
  line-height: 1.1rem;
  padding: 0;
  position: absolute;
  right: 0.5rem;
  top: 50%;
  transform: translateY(-50%);
  transition: transform 0.4s ease-in-out;
}

input:checked + label::before {
  content: url("https://d33wubrfki0l68.cloudfront.net/7468164d2fc2ad4fdea648e6cf2de622c2f70892/1819b/images/chevron-up.svg");
  transform: translateY(-50%) rotateZ(180deg);
}

input + label + .accordion-content {
  display: none;
}

input:checked + label + .accordion-content {
  display: block;
}

th, td {
  border-style: hidden;
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