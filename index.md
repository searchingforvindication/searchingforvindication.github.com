---
layout: page
title: Searching For Vindication
---
{% include JB/setup %}


## Latest Posts

<ul class="posts">
  {% for post in site.posts limit:4 %}
       <li class="post">
           <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> <span>({{ post.date | date: "%B %d,  %Y" }})</span>  
           <summary>{{ post.description | more: "excerpt" }}</summary>          
       </li>
  {% endfor %}
</ul>


<script type="text/javascript">
/* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
var disqus_shortname = 'searchingforvindication'; 

/* * * DON'T EDIT BELOW THIS LINE * * */
(function () {
var s = document.createElement('script'); s.async = true;
s.type = 'text/javascript';
s.src = 'http://' + disqus_shortname + '.disqus.com/count.js';
(document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
}());
</script>



