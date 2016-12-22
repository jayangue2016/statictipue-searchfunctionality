# statictipue-searchfunctionality
WELCOME TO TIPUE SEARCH ENGINE STATIC TYPE ULTIMATE NOOB GUIDE 

In order to add TIPUE SEARCH to your website you need to do the following

**** Add this code inside your <head></head> tag.

<!-- start copying here -->

<link type="text/css" rel="stylesheet" href="tipuesearch/tipuesearch.css"</link>
<script type="text/javascript" src="tipuesearch/jquery.min.js"></script>
<script type="text/javascript" src="tipuesearch/tipuesearch_set.js"></script>
<script type="text/javascript" src="tipuesearch/tipuesearch_content.js"></script>
<script type="text/javascript" src="tipuesearch/tipuesearch.min.js"></script>

<!-- end copying here -->

**** Add this code inside your <body></body> tag.
**** In the <form action="nameofyoursearchpage.html"> enter the name of the html page where you put this code.

<!-- start copying here -->

<!-- THIS IS THE SEARCH BOX -->
<form action="nameofyoursearchpage.html">
<input type="text" name="q" id="tipue_search_input" autocomplete="off" required>
</form>

<!-- THIS IS WHERE YOU DISPLAY THE SEARCH RESULTS -->
<div id="tipue_search_content"></div>

<!-- THIS JAVASCRIPT CODE DISPLAY THE SEARCH RESULTS -->
<script>
$(document).ready(function() {
     $('#tipue_search_input').tipuesearch();
});
</script>

<!-- end copying here -->

What are the uses of the following files inside the tipuesearch folder?

tipuesearch.css >> This is where you control the presentation of your search results
jquery.min.js >>> This script runs the tipue search (Replace this file with the latest version)
tipuesearch.min.js >>> Don't touch this file if you don't know what you are doing
tipuesearch_content.js >>> This is where you put what can be search in your website
tipuesearch_set.js >>> This is where you set the settings for your search engine
