---
title: Figure Skating Index
layout: index
---
<h1>Chinese Figure Skaters</h1>


<p class="para2">The 24th Olympic Winter Games (The XXIV Olympic Winter Games), the 2022 Beijing Winter Olympics, is scheduled to open on Friday, February 4, 2022, and close on Sunday, February 20. The Beijing Winter Olympics has 7 major events, 15 sub-events, and 109 minor events. Beijing competition area undertakes all ice events; Yanqing competition area undertakes snowmobile, sled and alpine skiing; Chongli District of Zhangjiakou competition area undertakes all snow sports except snowmobile, sled and alpine skiing .The theme slogan of the Beijing Winter Olympics is "Together to the future". On October 18th, the Beijing Winter Olympics successfully ignited in Greece. On October 20th, the Beijing Winter Olympics Tinder arrived in Beijing.</p>

<p class="para2">Figure skating is a sport in which individuals, pairs, or groups perform on figure skates on ice. It was the first winter sport to be included in the Olympic Games, when contested at the 1908 Olympics in London. The Olympic disciplines are men's singles, women's singles, pair skating, and ice dance; the four individual disciplines are also combined into a team event, first included in the Winter Olympics in 2014.</p>

<p class="para2">This website mainly includes well-known figure skaters in China and their main achievements.</p>

<div class="line2"></div>
    
<div class="gallary">  
    {% for name in site.men %}
        <div class="card">
         <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
         <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
 </div>   
{% endfor %} 
</div>  

<div class="line2"></div>
    
<div class="gallary">  

{% for name in site.women %}
          <div class="card">
            <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
            <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
          </div>    
{% endfor %}
</div>  

<div class="line2"></div>
    
<div class="gallary">  
{% for name in site.pair %}
   <div class="card">
     <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
     <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
    </div>  
{% endfor %}
</div>  





This work is licensed under a
[Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/)
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC_BY--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)


