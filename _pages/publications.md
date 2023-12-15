---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<div><h2> Publications </h2></div>
<hr style="border-color:black;">
{% for post in site.research reversed %}
  {% if post.PublicationStatus == 'Published' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<div><h2> Working Papers </h2> </div>
<hr style="border-color:black;">
{% for post in site.research reversed %}
  {% if post.PublicationStatus == 'WorkingPaper' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
 

 <div><h2> Work in Progress </h2></div>
 <hr style="border-color:black;">
{% for post in site.research reversed %}
  {% if post.PublicationStatus == 'WorkInProgress' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div><h3> Keywords </h3></div>
{% include tags_names.html %}
{% assign button_style = 'margin: 5px;font-size: 12px; ;;padding:5px 10px 5px 10px;background:white;color:#black;outline:none;border-radius:3px;border: 1px solid black;' %}
<div>
    {% for tag_sample in tags_names %}
  	<button id = "b_{{tag_sample}}" onclick="checked('{{tag_sample}}')" style="{{button_style}}" onmouseover="func_hover('b_{{tag_sample}}')" onmouseout= "func_out('{{tag_sample}}')">
	<input type="checkbox" id="{{tag_sample}}"  checked=checked style="margin-right:8px">{{tag_sample}}</button>
    {%endfor%}
    
</div>
