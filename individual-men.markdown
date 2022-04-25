---
layout: index
title: Individual Men
permalink: /individual-men/
---
<h1> Individual Men</h1>

<p class="para">The Chinese men's single skaters boast a strong technical level, they were able to complete quad jumps back in the 90s, which are the highest difficulty skating skills even in current competitions. Most of the men's skaters maintain their score between 10th to 20th in the World Figure Skating Championships, with the best result set by Jin Boyang, who placed the 4th at the 2018 Winter Olympics in Pyeongchang. Often, the men's performances incorporate Chinese Kongfu, such as Li Chengjiang and Kim Boyang's ‘Crouching Tiger, Hidden Dragon’.

</p>

<div class="line2"></div>
    
<div class="gallary">  
    {% for name in site.men %}
        <div class="card">
         <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
         <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
 </div>   
{% endfor %} 
</div>  


