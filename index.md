---
layout: default
title: "HCI Project"
---
<div class="container">
{% for i in site.data.data %}
  <div class="card">
    <div class="box">
      <div class="content">
        <h3>{{ i.name }}</h3>
        <p>{{ i.description}}</p>
        {% for technology in i.technologies %}
        <a href="#">{{ technology }}</a>
        {% endfor %}
      </div>
    </div>
      </div>
    {% endfor %}
  </div>
 
