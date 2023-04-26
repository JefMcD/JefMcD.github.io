# CS50_Project0

Notes on the project 0 

General
--------
Responsive design in the style of Google search page and advanced search page. Website adapts to mobile and desktop

image-search-parameters.txt
---------------------------
contains some urls sent to google to look at the GET parameters with their key=value pairs. This reveals the name used for each parameter that you need to do different types of searches.

Standard search. requires the input field to have name = "q"

Google image search has a bunch of parameters that get sent but I found that the only one's necessary are for the input to have search field input name = "q" and an additional parameter of 
tbm = "isch" that Ive supplied using a hidden input field.

Each Advanced Search field supplies a unique name identifier as described below


index.html
-----------
buttons on top right in style of Google buttons for links to Image Search Page and Advanced Search Page.

Main Search Field and two buttons underneath. One for Google Search and One for Lucky Search. search parameter suppled by search field  name="q"

With the Lucky search I used code skimmed from the Google Site and plugged in the values that Google uses to do the Lucky search. Google specifically gives the Lucky Search Button the name="btnI" and it doesnt work without this together with a value of "I'm Feeling Lucky". It also supplies the parameter 'ved' which appears to have a consistent value but it works without it so I left it out.

image-search.html
-----------------

Top Left button that returns user to the standard search page, Logo indicating Image Search
Search field. Single button below that submits image search. Search field supplies parameter name="q" with hidden input supplying parameter name="tbm" with value="isch"


advanced.html
---------------
Top Right Button to return to standard search page and logo section to the left indicating Advanced Search.
Design follows the Google advanced search design, with square looking boxes and three columns that fold down into two on small screens

search field input name = 
"as_q" (All Words)
"as_eq" (Exact Words)
"as_oq" (This word OR that word)
"as_eq" (As exact words but with minus sign ie "-blue")


IfeelLuckyGoogle.html
----------------------
This is the Google Code for the Standard Search Button and the I'm Feeling Lucky Button





