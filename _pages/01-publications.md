---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2022, 2021, 2020, 2019, 2018, 2017,2016,2015,2014,2013,2012,2011,2010, 2009,2008, 2007]
nav: true
---

Please check my **[GoogleScholar profile](https://scholar.google.com.tr/citations?hl=tr&user=LXUvnL0AAAAJ&view_op=list_works&sortby=pubdate)** for a full list of publications.

{% comment %}
<style>
div.bibyear {
    font-family: Verdana, Arial, Helvetica, sans-serif;
    font-size: 150%;
    font-weight: bold;
}

div.bibdoi {
    display: inline;
}

div.bibtitle {
    color: #000000;
    font-weight: bold;
}

div.bibauthor {
    display: inline-block;
}

div.bibauthors {
    font-style: italic;
}

div.bibauthors a:link, a:visited {
    color: #000000;
    text-decoration: none;
    font-weight: normal;
}

div.bibauthors a:hover {
    color: #000000;
    text-decoration: underline;
}
</style>

Please check my **[GoogleScholar profile](https://scholar.google.com.tr/citations?user=LXUvnL0AAAAJ)** for a full list of publications.

<!-- _pages/publications.md -->
<div class="publications">

<!-- This div is a placeholder which will contain the publications -->
<div id="pubszone">
  Loading publications...
</div>
<!-- Function which will handle the content received through JSONP -->
<script type='text/javascript'>
//<![CDATA[
    function mycallback(ad_content) {
    	document.getElementById('pubszone').innerHTML = ad_content.html;
    }
//]]>
</script>
<!-- Load of the remote JS which will call the callback function -->
<script src="https://www.csauthors.net/kasim-sinan-yildirim/embed/bib.js?callback=mycallback"></script>
    
        
<!-- _pages/publications.md -->
<div class="publications">
    
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
    
</div>
    
{% endcomment %}