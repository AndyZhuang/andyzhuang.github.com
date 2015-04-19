---
layout: page
title: AZ Blog   
tagline:        recording the fantastic journey
---
{% include JB/setup %}

### Recently working on
On April.19th

    
    1. A Maker/Hacker Space in Beijing , due in June.
    2. A secret Science App project, due in May, prepare to be amazed.
    
    

### Recently Studying
On April.19th
    
    * Linux Admin. (IPtable, Scripting, etc)
    * Docker, Vagrantup, etc
    * SDR, HackRF etc.
    

### Product recommended
on Mar. 24th.
    
    1. www.simplexue.com,  awesome site to learn hacking
    2. Hiwifi, it is much simpler and safer
    3. the Movie , bigHero6, so full of maker spirit

### My Posts 

<ul class="posts">
  {% for post in site.posts %}
       <li>
       <span>{{ post.date | date_to_string }}</span> &raquo; 
<a href="{{BASE_PATH }}{{ post.url}}"> {{ post.title }} </a>
       </li>
  {% endfor %}
</ul>










