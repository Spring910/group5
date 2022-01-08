---
layout: index
title: Individual Women
permalink: /individual-women/
---

<h1> Individual Women </h1>
<p class="para">Single Women skating is a discipline of figure skating in which female skaters compete individually. Men's singles and women's singles, along with the other figure skating disciplines of pair skating, ice dance, and synchronized skating, are governed by the International Skating Union (ISU). Figure skating is the oldest winter sport contested at the Olympics, with men's and women's single skating appearing as two of the four figure skating events at the London Games in 1908.
Single skaters are required to perform two segments in all international competitions, the short program, and the free skating program.
Single skating has required elements that skaters must perform during a competition and that make up a well-balanced skating program. They include jumps (and jump combinations), spins, step sequences, and choreographic sequences. The ISU defines a jump element as "an individual jump, a jump combination or a jump sequence". The six most common jumps can be divided into two groups: toe jumps (the toe loop, the flip, and the Lutz) and edge jumps (the Salchow, the loop, and the Axel). A jump combination, defined as "two (or more) jumps performed in immediate succession". There are three basic positions in spins: the camel, the sit spin, and the upright spin. Step sequences have been defined as "steps and turns in a pattern on the ice". A choreographic sequence, which occurs during the free skating program in singles skating, "consists of any kind of movements like steps, turns, spirals, arabesques, spread eagles, Ina Bauers, hydroblading, any jumps with maximum of 2 revolutions, spins, etc.".
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

