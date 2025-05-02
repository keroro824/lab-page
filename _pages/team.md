---
title: "InfiniAI Lab - Team"
layout: gridlay
excerpt: "InfiniAI Lab: Team members"
sitemap: false
permalink: /people/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)](https://keroro824.github.io/lab-page/vacancies) **!**

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="https://keroro824.github.io/lab-page/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | markdownify}} </li>
  <li> {{ member.education2 | markdownify}} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Alumni
<div class="row">
<div class="col-sm-6 clearfix">
<p><b>Visitors and Bachelor/ Master students</b></p>
<p><span color="blue">Hanshi Sun (MS)</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Bytedance</p>
<p><span color="blue">Jian Chen (MS)</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (UCSD)</p>
<p><span color="blue">Haoyun Chen (MS)</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (Sakana AI)</p>
<p><span color="blue">Jingwei Zuo (MS)</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (Rice University)</p>
<p><span color="blue">Vashisth Tiwari (MS)</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CMU</p>
<p><span color="blue">Chen Li (MS)</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CMU</p>
<p><span color="blue">Yiying Luo (MS)</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CMU</p>
<p><span color="blue">Wentao Guo (MS)</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Princeton University</p>

</div>
</div>


