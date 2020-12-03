# code-refactor-hw

Deployment link:  https://khsieh95.github.io/code-refactor-hw/ 

This repository is in reference to the first homework assignment, where we were asked to optimize  a site 
in terms of the accessibility standards. Changes were made to both the index.html and style.css files in 
order to clean up and organize their functions. 

<h1>index.html files changes:<h1>
<!-- Removed div tags and replaced with semantics -->
<img width="1440" alt="Screen Shot 2020-12-03 at 12 19 19 PM" src="https://user-images.githubusercontent.com/74025123/101083735-d36a7000-3561-11eb-8486-1ebe6b49f10f.png">

Prior to the changes I made (didn't get a screenshot), index.html was strictly made of div tags. In order 
to clean up the structure, all div tags were removed and replaced with semantic tags such as header ,nav, figure, footer and many more. Refer to screenshot link. 

Minor changes include changing the last header tag from h2 to h4 because headers should get smaller as we go down the site.

For accessibility purposes, alt tags were added following all img src tags

<h2>style.css changes:<h2>
Combined tags that had the same changes
<img width="1440" alt="Screen Shot 2020-12-03 at 12 15 00 PM" src="https://user-images.githubusercontent.com/74025123/101083139-648d1700-3561-11eb-8311-e83427c8ede9.png">

Prior to changes, there were a lot of redundant codes to seperate classes. I combined the classes into one line followed by attaching the code. 

For example: 
.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

Changed to... 
.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
} 
(refer to screenshot)

All css tags were adjusted accordingly to html changes

Got rid of div classes in html, therefore css tags did not use a "."
Before: html div class= "header" css .header {}
After: html header css header {} 

Both the index.html and style.css have been optimized in such a way that the code is cleaner and more simplified, without damaging the existing site.