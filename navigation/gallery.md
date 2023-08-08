---
layout: default
permalink: /:basename/
title: Photography · Abraham Thomas
---

<head>
<style>

#content {
  margin-top: 15px;
}

table {
  border-collapse: collapse;
}
table, th, td {
  padding: 3px;
  line-height: 0;
}
</style>
</head>

<body>

<!--
{% for item in site.data.photos %}   
  {% if item.album != "newline" %}  
     <a href="/gallery#{{ item.album }}"> {{item.album}} &emsp; &emsp;</a>
  {% endif %}
{% endfor %}
-->

{% for item in site.data.photos %}   
  {% if item.album != "newline" %}
    <br/>
    <br/>
    <br/>
    <h2 id="{{ item.album }}"> {{ item.album }} </h2>
    <br/>
  {% endif %}
    <table>
      <tr>
        {% for pic in item.pictures %} 
          <td><a href="{{ pic.link }}"><img src="{{ pic.smol }}" width="{{ pic.width }}"></a></td>
        {% endfor %}
      </tr>
    </table>
{% endfor %}
<br/>
<br/>
<br/>

</body>
