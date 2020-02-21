---
layout: default
title: Travel · Abraham Thomas
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
{% for item in site.data.photos %}   
  {% if item.album != "newline" %}
    <br/>
    <br/>
    <br/>
    <h3> {{ item.album }} </h3>
    <br/>
  {% endif %}
    <table>
      <tr>
        {% for pic in item.pictures %} 
          <td> 
            <a href="{{ pic.link }}">
              <img src="{{ pic.smol }}" width="{{ pic.width }}"> 
            </a>
          </td>
        {% endfor %}
      </tr>
    </table>
{% endfor %}
</body>
