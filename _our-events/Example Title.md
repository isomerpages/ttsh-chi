---
title: Example Title
permalink: /our-events/example/
description: ""
---
<h1>How TO - Overlay</h1>
<div class="w3-clear nextprev">
<a class="w3-left ws-btn" href="howto_css_user_rating.asp">❮ Previous</a>
<a class="w3-right ws-btn" href="howto_css_contact_chips.asp">Next ❯</a>
</div>
<hr>
<p class="intro">Learn how to create an overlay effect with CSS.</p>
<hr>

<h2>Overlay</h2>
<p>Learn how to create an overlay effect:</p>
<div id="overlay" title="Click to turn off the overlay effect">
<div class="text">Overlay</div>
<div class="text"><br>
<br><span style="font-size:20px;" class="w3-black w3-padding w3-hide-medium w3-hide-small">Click anywhere to turn off the overlay effect</span></div>
</div>

<button class="w3-button ws-green">Turn on the overlay effect</button>


<hr>

<h2>How To Create an Overlay Effect</h2>
<h5>Step 1) Add HTML:</h5>
<p>Use any element and place it anywhere inside the document:</p>

<div class="w3-example">
<h3>Example</h3>
<div class="w3-code notranslate htmlHigh">
  &lt;div id="overlay"&gt;&lt;/div&gt;</div>
</div>
<hr>
<h5>Step 2) Add CSS:</h5>
<p>Style the overlay element:</p>
<div class="w3-example">
<h3>Example</h3>
<div class="w3-code notranslate cssHigh">
  #overlay {<br>&nbsp; position: fixed; /* Sit on top of the 
  page content */<br>&nbsp; 
  display: none; /* Hidden by default */<br>&nbsp; width: 100%; /* 
  Full width (cover the whole page) */<br>&nbsp; 
  height: 100%; /* Full height (cover the whole page) */<br>&nbsp; top: 0; <br>&nbsp; left: 0;<br>&nbsp; 
  right: 0;<br>&nbsp; bottom: 0;<br>&nbsp; 
  background-color: rgba(0,0,0,0.5); /* Black background with opacity */<br>&nbsp; z-index: 2; 
  /* Specify a stack order in case you're using a different order for other 
  elements */<br>&nbsp; 
  cursor: pointer; /* Add a pointer on hover */<br>}</div>
</div>
<hr>
<div id="midcontentadcontainer" style="overflow:auto;text-align:center">
<!-- MidContent -->
<!-- <p class="adtext">Advertisement</p> -->

  <div id="adngin-mid_content-0"></div>
  
</div>
<hr>

<h5>Step 3) Add JavaScript:</h5>
<p>Use JavaScript to turn on and off the overlay effect:</p>
<div class="w3-example">
<h3>Example</h3>
<div class="w3-code notranslate jsHigh">
  function on() {<br>&nbsp;&nbsp;document.getElementById("overlay").style.display 
  = "block";<br>}<br><br>function off() {<br>&nbsp;&nbsp;document.getElementById("overlay").style.display = "none";<br>}</div>
<a target="_blank" href="tryit.asp?filename=tryhow_css_overlay" class="ws-btn w3-margin-bottom">Try it Yourself »</a>
</div>
<hr>

<h2>Overlay Effect with Text</h2>
<p>Add anything you want inside the overlay, and place it where you want. In this example we add text in the middle of the page:</p>
<div class="w3-example">
<h3>Example</h3>
<div class="w3-code notranslate htmlHigh">
  &lt;style&gt;<br>#text{<br>&nbsp; position: absolute;<br>&nbsp;&nbsp;top: 50%;<br>&nbsp;&nbsp;left: 50%;<br>
  &nbsp; font-size: 
  50px;<br>&nbsp; color: white;<br>&nbsp; transform: 
  translate(-50%,-50%);<br>&nbsp; -ms-transform: 
  translate(-50%,-50%);<br>}<br>&lt;/style&gt;<br><br>&lt;div id="overlay"&gt;<br>&nbsp; 
  &lt;div id="text"&gt;Overlay Text&lt;/div&gt;<br>&lt;/div&gt;</div>
<a target="_blank" href="tryit.asp?filename=tryhow_css_overlay_text" class="ws-btn w3-margin-bottom">Try it Yourself »</a>
</div>
<br>

<br>
<div class="w3-clear nextprev">
<a class="w3-left ws-btn" href="howto_css_user_rating.asp">❮ Previous</a>
<a class="w3-right ws-btn" href="howto_css_contact_chips.asp">Next ❯</a>
</div>
<div id="mypagediv2" style="position:relative;text-align:center;"></div>
<br>


<div class="w3-col l2 m12" id="right">

<div class="sidesection">
  <div id="skyscraper">
  
    <div id="adngin-sidebar_top-0"></div>
  
  </div>
</div>
  
<style>
.ribbon-vid {
  font-size:12px;
  font-weight:bold;
  padding: 6px 20px;
  left:-20px;
  top:-10px;
  text-align: center;
  color:black;
  border-radius:25px;
}
</style>

<div class="sidesection" style="margin-top:20px;margin-bottom:20px;">
<a id="upperfeatureshowcaselink" class="ga-right" href="https://campus.w3schools.com/collections/course-catalog/products/w3schools-full-access-course" target="_blank">
<picture id="upperfeatureshowcase">
  <source id="upperfeatureshowcase3001" srcset="/images/img_fullaccess_up_purple_300.png" media="(max-width: 990px)" style="border-radius: 5px;">
  <source id="upperfeatureshowcase120" srcset="/images/img_fullaccess_up_purple_120.png" media="(max-width: 1260px)" style="border-radius: 5px;">
  <source id="upperfeatureshowcase160" srcset="/images/img_fullaccess_up_purple_160.png" media="(max-width: 1700px)" style="border-radius: 5px;">
  <img id="upperfeatureshowcase300" src="/images/img_fullaccess_up_purple_300.png" alt="Unlock Full Access" style="width:auto;border-radius: 5px;">
</picture>
</a>
</div>

<div class="sidesection">
<h4><a href="/colors/colors_picker.asp">COLOR PICKER</a></h4>
<a href="/colors/colors_picker.asp" class="ga-right">
<img src="/images/colorpicker2000.png" alt="colorpicker" loading="lazy">
</a>
</div>

<div class="sidesection">
  <div class="sharethis">
    <a href="https://www.facebook.com/w3schoolscom/" target="_blank" title="Facebook"><span class="fa fa-facebook-square fa-2x ga-right"></span></a>
    <a href="https://www.instagram.com/w3schools.com_official/" target="_blank" title="Instagram"><span class="fa fa-instagram fa-2x ga-right"></span></a>
    <a href="https://www.linkedin.com/company/w3schools.com/" target="_blank" title="LinkedIn"><span class="fa fa-linkedin-square fa-2x ga-right"></span></a>
    <a href="https://discord.gg/6Z7UaRbUQM" target="_blank" title="Join the W3schools community on Discord"><span class="fa fa-discord fa-2x ga-right"></span></a> 
  </div>
</div>

<div class="sidesection" style="margin-top:20px;margin-bottom:20px;">
<a id="lowerfeatureshowcaselink" class="ga-right" href="https://www.w3schools.com/bootcamp/bootcamp_htmlcss.php" target="_blank">
<picture id="lowerfeatureshowcase">
  <source id="lowerfeatureshowcase3001" srcset="/images/img_bootcamp_green_300.png" media="(max-width: 990px)" style="border-radius: 5px;">
  <source id="lowerfeatureshowcase120" srcset="/images/img_bootcamp_green_120.png" media="(max-width: 1260px)" style="border-radius: 5px;">
  <source id="lowerfeatureshowcase160" srcset="/images/img_bootcamp_green_160.png" media="(max-width: 1700px)" style="border-radius: 5px;">
  <img id="lowerfeatureshowcase300" src="/images/img_bootcamp_green_300.png" alt="Join our Bootcamp!" style="width:auto;border-radius: 5px;">
</picture>
</a>
</div></div>