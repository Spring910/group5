---
layout: index
title: Ice Dancing
permalink: /ice-dancing/
---

<h1>Ice Dancing</h1>
<p class="para">Ice dancing is a discipline of figure skating that historically draws from ballroom dancing. It joined the World Figure Skating Championships in 1952 and became a Winter Olympic Games medal sport in 1976. According to the International Skating Union (ISU), the governing body of figure skating, an ice dance team consists of one woman and one man.
Ice dance, like pair skating, has its roots in the "combined skating" developed in the 19th century by skating clubs and organizations and in recreational social skating. Couples and friends would skate waltzes, marches, and other social dances. The first steps in ice dance were similar to those used in ballroom dancing. In the late 1800s, American Jackson Haines, known as "the Father of Figure Skating", brought his style of skating, which included waltz steps and social dances, to Europe. By the end of the 19th century, waltzing competitions became popular throughout the world. By the early 1900s, ice dance was popular around the world and was primarily a recreational sport, although during the 1920s, local clubs in Britain and the U.S. conducted informal dance contests. Recreational skating became more popular during the 1930s in England.
Before the 2010–11 figure skating season, there were three segments in ice dance competitions: the compulsory dance (CD), the original dance (OD), and the free dance (FD). In 2010, the ISU voted to change the competition format by eliminating the CD and the OD and adding the short new dance (SD) segment to the competition schedule. In 2018, the ISU voted to rename the short dance to the rhythm dance (RD). Ice dance has required elements that competitors must perform and that make up a well-balanced skating program. They include the dance lift, the dance spin, the step sequence, twizzles, and choreographic elements. These must be performed in specific ways, as described in published communications by the ISU, unless otherwise specified. Each year the ISU publishes a list specifying the points that can be deducted from performance scores for various reasons, including falls, interruptions, and violations of the rules concerning time, music, and clothing.
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
