---
layout: default
title: Desintations
comments: false
permalink: destinations
---

<h1>{{ page.title }}</h1>

<div id="container" style="position: relative; height: 600px;"></div>
<script>
    var map = new Datamap({element: document.getElementById('container')});
</script>



<section class="recent-posts">
    <div class="section-title">
        <h2><span>Asia</span></h2>
    </div>
    <div class="masonrygrid row listrecent">

 {% for post in site.posts %}
    
    {% if post.categories contains "asia" %}
 
        {% include postbox.html %}

{% endif %}

{% endfor %}

</div>

</section>

<section class="recent-posts">
    <div class="section-title">
        <h2><span>Africa</span></h2>
    </div>
    <div class="masonrygrid row listrecent">
    </div>
</section>


<section class="recent-posts">
    <div class="section-title">
        <h2><span>Europe</span></h2>
    </div>
    <div class="masonrygrid row listrecent">

     {% for post in site.posts %}
    
    {% if post.categories contains "europe" %}
 
        {% include postbox.html %}

{% endif %}

{% endfor %}

    </div>
</section>


<section class="recent-posts">
    <div class="section-title">
        <h2><span>North America</span></h2>
    </div>
    <div class="masonrygrid row listrecent">
    </div>
</section>


<section class="recent-posts">
    <div class="section-title">
        <h2><span>South America</span></h2>
    </div>
    <div class="masonrygrid row listrecent">
    </div>
</section>


<section class="recent-posts">
    <div class="section-title">
        <h2><span>Oceanoia</span></h2>
    </div>
    <div class="masonrygrid row listrecent">
    </div>
</section>