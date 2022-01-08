---
layout: index
title: Pair Skating
permalink: /pair-skating/
---

<h1>Pair Skating</h1>
<p class="para">Pair skating is a figure skating discipline defined by the International Skating Union (ISU) as "the skating of two persons in unison who perform their movements in such harmony with each other as to give the impression of genuine Pair Skating as compared with independent Single Skating". The ISU also states that a pairs team must consist of "one Lady and one Man". Pair skating, along with men's and women's single skating, has been an Olympic discipline since figure skating, the oldest Winter Olympic sport, was introduced at the 1908 Summer Olympics in London. The ISU World Figure Skating Championships introduced pair skating in 1908.
Like the other disciplines, pair skating competitions consist of two segments, the short program and the free skating program. There are seven required elements in the short program, which lasts 2 minutes and 40 seconds for both junior and senior pair teams. Free skating for pairs "consists of a well-balanced program composed and skated to music of the pair's own choice for a specified period of time". It also should contain "especially typical Pair Skating moves" such as pair spins, lifts, partner assisted jumps, spirals, and other similar moves, "linked harmoniously by steps and other movements". Its duration, like the other disciplines, is 4 minutes for senior teams, and 3+1⁄2 minutes for junior teams. Pair skating required elements include lifts, twist lifts, throw jumps, jumps, spin combinations, death spirals, step sequences, and choreographic sequences. The elements performed by pairs teams must be "linked together by connecting steps of a different nature" and by other comparable movements and with a variety of holds and positions. Pair skaters must only execute the prescribed elements; if they do not, the extra or unprescribed elements will not be counted in their score. Violations in pair skating include falls, time, music, and clothing.
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
