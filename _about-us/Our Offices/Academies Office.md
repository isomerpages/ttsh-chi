---
title: Academies Office
permalink: /about-us/our-offices/academies-office/
variant: markdown
description: ""
third_nav_title: Our Offices
---
<h2> CHI Academies Office </h2> 

The Academy Office is a central management body supporting three key academies under Centre for Healthcare Innovation (CHI): CHI Value Academy (CHI VA), CHI Sustainability Academy (CHI SA), and CHI Health and Social Change Academy (CHI HSCA). 

Each academy plays a vital role in advancing healthcare practices, sustainability efforts, and community well-being, collectively contributing to CHI's mission of driving innovation and positive change in the healthcare sector.

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
  content: url("/images/chevron-down.svg");
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
  content: url("/images/chevron-up.svg");
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

<div>
	<input id="title1" type="checkbox"><label for="title1">	CHI Health and Social Change Academy</label>
	<div class="accordion-content">
	<div class="para">Facilitate agreements that safeguard the hospital and its stakeholders’ interests. These agreements ensure that every study/ trial is conducted according to all applicable laws and regulations, and the relevant ethics and regulatory requirements 
</div>
	</div>
	<input id="title2" type="checkbox"><label for="title2">CHI Sustainability Academy</label>
	<div class="accordion-content">
	<div class="para">The Clinical Trials Unit is made up of a team of GCP- (Good Clinical Practice) and CITI (Collaborative Institutional Training Initiative)-certified clinical research coordinators who conduct both early and late phase trials. To find out more, please contact <a href="mailto:clinicaltrial@ttsh.com.sg">clinicaltrial@ttsh.com.sg</a>.
</div>
	</div>
		</div>
<div>		
<input id="title3" type="checkbox"><label for="title3">CHI Value Academy</label>
	<div class="accordion-content">
	<div class="para">Clinical Research Support (CRS) unit consists of medical statisticians and epidemiologist that work closely with researchers through the research process; from the conceptualisation of ideas, developing study protocols, collecting and analysing the relevant data, and publication of research findings.
</div>
	</div></div>