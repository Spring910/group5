---
layout: index
title: Individual Women
permalink: /individual-women/
---

<h1> Individual Women </h1>
<p class="para">The best result of Chinese lady single skating was set by Lu Chen, who won the World Figure Skating Champion in 1995. Apart from her, most of the Chinese lady single skaters have finished their competition around 15th-25th at the World Figure Skating Championships. Despite their weak technical skills, the skaters possess their unique charisma, present soft, elegance and femininity. 
</p>

<div class="line2"></div>
    
<div class="gallary">  

{% for name in site.women %}
          <div class="card">
            <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
            <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
          </div>    
{% endfor %}
</div>  

