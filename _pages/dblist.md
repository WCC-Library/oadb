<ul>
{% for item in site.data.summer_2019 %}
<li>
<a href="{{item.URL}}">{{item.'Product Name'}}
</a></li>
{% endfor %}
</ul>
