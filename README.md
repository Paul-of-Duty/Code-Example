Code-Example
============

Exaple of Code from my Major project. Worked with PHP, HTML and CSS. Below is the code from a FAQ page for the website. Content is jibberish as an NDA was signed for this project.


<?php

	$title = 'Indulgence | F.A.Q';
	
	$maincontent = '
    <div id="FAQHeader">
		<h1 style="text-align: left"><a id="head">Frequently</a></h1>
		<h1 style="text-align: center">Asked</h1>
		<h1 style="text-align: right">Questions</h1>
	</div>
	
		<div id="FAQRht_Col">
	<h2><a id="q1">Question 1</a></h2> 
	<p>
	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla lacus, dapibus a blandit et, pretium a mauris. Morbi ut nisl bibendum, varius ex sit amet, imperdiet tellus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed venenatis urna sit amet fermentum ultricies. Donec tincidunt felis id tristique vehicula. Donec at nunc sed ligula mollis posuere. Maecenas ex urna, facilisis in felis nec, laoreet feugiat tortor. 
	<h5 class="hyperlink1"><a href="#head">Back to Top</a></h5>
	</p>

	<h2><a id="q2">Question 2</a></h2>
	<p>
	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla lacus, dapibus a blandit et, pretium a mauris. Morbi ut nisl bibendum, varius ex sit amet, imperdiet tellus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed venenatis urna sit amet fermentum ultricies. 
	<h5 class="hyperlink1"><a href="#head">Back to Top</a></h5>
	</p>

	<h2><a id="q3">Question 3</a></h2>
	<p>
	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla lacus, dapibus a blandit et, pretium a mauris. Morbi ut nisl bibendum, varius ex sit amet, imperdiet tellus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed venenatis urna sit amet fermentum ultricies. 
	<h5 class="hyperlink1"><a href="#head">Back to Top</a></h5>
	</p>

	<h2><a id="q4">Question 4</a></h2>
	<p>
	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nulla lacus, dapibus a blandit et, pretium a mauris. Morbi ut nisl bibendum, varius ex sit amet, imperdiet tellus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed venenatis urna sit amet fermentum ultricies. 
	<h5 class="hyperlink1"><a href="#head">Back to Top</a></h5>
	</p>
	</div>
	
	<br/>
	<br/>
	
	<div id="FAQLft_Col" style="float:left">
		<h2 class="hyperlink1"><a href="#q1">Question 1</a></h2>
		<h2 class="hyperlink1"><a href="#q2">Question 2</a></h2>
		<h2 class="hyperlink1"><a href="#q3">Question 3</a></h2>
		<h2 class="hyperlink1"><a href="#q4">Question 4</a></h2>
	</div>

	</body>
	
	';
	
	include('master.php');
?>
