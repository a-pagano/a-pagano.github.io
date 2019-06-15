---
layout: post
title:  "Sustainable clothes"
date:   2019-06-15 23:51:53 +0200
categories: clothes
---
<!-- Pulls from _data links -->
{% assign links = site.data.links %}
{% assign links = links | sort:"Name" %}

<h3>Links</h3>
<table width="100%">
{% for link in links %}
  <tr>
    <td><strong>{{ link.name }}</strong></td>
    <td width="25%">{{ link.url }}</td>
  </tr>
{% endfor %}
</table>
