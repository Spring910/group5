---
layout: index
title: Ice Dancing
permalink: /ice-dancing/
---

<h1>Ice Dancing</h1>
<p class="para">The best performance in Chinese ice dancing was accomplished by Shi Yue Wang/Xinyu Liu, who finished 12th at the 2022 Winter Olympics in Beijing. Although Chinese ice dancer skaters still have a lot to learn in terms of technical and performance skills, they have worked hard to bring the Chinese story and oriental appeal to the globe, shattering the supremacy of European and American skaters in this discipline. Shi Yue Wang/Xinyu Liu's 12th place finish in the Winter Olympics was the best ever for Asian ice dancers.
</p>
<div class="line2"></div>
    
<div class="gallary">  
{% for name in site.dance %}
        <div class="card">
          <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
          <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
        </div>   
{% endfor %}
</div>  
