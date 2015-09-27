----
layout: page
title: AZ Blog   
tagline:        recording the fantastic journey
----
{% include JB/setup %}

### Starting lines

1. For the last several months , I built the Starship Space and got several
teams in the incubator, moreover, I am so into biology and sequencing industry 
and try to build a new company. So much to learn, and so fun to dive into
it.Everyday it is like a new adventure to me. Not sure if I am too cocky on the
dicision, but at least I enjoy it quite a lot. 
2. Recently I watched zhaowei's address on web security and quite impressed
with the quote he used , it is Einstein's quote, saying "it is dangerous place
to live not because of the people who are evil, but because of the people who
don't do anything about it". My heart ached just by thinking about it.
3. Anyway, I am back, and continue to cultivate with this blog. 


### Recently working on
On Sep.27th

    
1. A sequencing company
2. My own hacking
    
    

### Recently Studying
On Sep.27th
    
    * Biology NGS
    * Bioinformatics
    * Ruby
    

### Product recommended
On Sep.27th

    
1. www.freebuf.com
2. www.starshipff.com
3. Geek Gene maybe
    

### My Posts 

<ul class="posts">
  {% for post in site.posts %}
       <li>
       <span>{{ post.date | date_to_string }}</span> &raquo; 
<a href="{{BASE_PATH }}{{ post.url}}"> {{ post.title }} </a>
       </li>
  {% endfor %}
</ul>










