---
layout: index
title: Pair Skating
permalink: /pair-skating/
---

<h1>Pair Skating</h1>
<p class="para">The Chinese pairs skaters are world-class athletes. Two couples, Xue Shen/ Hongbo Zhao and Wenjing Sui/ Cong Han, winning gold medals in pair skating at the 2010 and 2022 Winter Olympics respectively. Technically, the Chinese pairs skaters have top twist lifts and death spirals skills, and in terms of sequences, the athletes have even learned ice dancing techniques in the hopes of achieving dance-like skating; artistically, ‘It was a masterful blend of technical expertise, thoughtful choreography and an emotionally powerful performance’, commented by Sandra Bezic(2022), who was one of the greatest skating choreographers.
</p>

<div class="line2"></div>
    
<div class="gallary">  
{% for name in site.pair %}
   <div class="card">
     <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
     <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
    </div>  
{% endfor %}
</div>  
