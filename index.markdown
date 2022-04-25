---
title: Figure Skating Index
layout: index
---
<h1>Chinese Figure Skaters</h1>


<p class="para">Although figure skating is a sport with a long history, having been included in the Olympic programme as early as 1908, it was not until 1986 that China formed its own national team. As a country with a predominantly subtropical and temperate climate, Chinese have insufficient knowledge about winter sports, many people didn't know about figure skating for the first time until the 2022 Olympics. To date, in China, 87% of winter sports athletes are come from the northeast China (Jilin, Liaoning and Heilongjiang, three of the coldest provinces in China); among figure skaters Olympians, only three of them are non-northeasterners. 
</p>

<p class="para">In regard of the skills, training methods and coaching level, there is still a gap between Chinese figure skaters and the top skaters. However, there are talented skaters such as Lu Chen, Chengjiang Li, Xue Shen \ Hongbo Zhao and Shiyue Wang \ Xinyu Liu, who not only have good technical skills, but also incorporate Chinese cultural elements in their performances They have contributed to the cultural diversity of figure skating by showing Chinese beauty in the world arena. For example, Chen Lu's 'Liang Zhu', Li Chengjiang's 'Crouching Tiger, Hidden Dragon' and Wang Shi Yue Liu Xinyu's 'Kung Fu Panda' are performances that have inspired Chinese skaters around the world and since them, there have slowly been more Chinese element performance on the ice arena.
</p>

<p class="para">The 2022 Winter Olympics will be the first Winter Olympics in China. In anticipation of the Olympics, China has invested a great deal of resources in the development of winter sports, and in the five years since the successful bid for the Olympics, the number of people participating in winter sports nationwide has reached 346 million, with a 24.56% participation rate of the population. What kind of development will the Beijing Olympics bring to Chinese figure skating? We’ll see.
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

<div class="line2"></div>
    
<div class="gallary">  
{% for name in site.dance %}
        <div class="card">
          <a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
          <p class="card-name"><a href = "{{ name.url | relative_url }}">{{ name.name }}</a></p>
        </div>   
{% endfor %}
</div>  



This work is licensed under a
[Creative Commons Attribution-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nd/4.0/)
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC_BY--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)


