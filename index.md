---
layout: page
title: AZ Blog   
tagline:        recording the fantastic journey
---
{% include JB/setup %}

### Recently working on
On Mar.24th.

    
    1. A Maker/Hacker Space in Beijing , due in June.
    2. A E-commerce site for open-source hardware, due in May.
    3. A Crowdfunding site for Science project,etc, due in April
    
    

### Recently Studying
On Mar. 24th. 
    
    * Linux Admin. (IPtable, Scripting, etc)
    * Ruby
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










