---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<section class="box">
	{% for map in site.maps %}
    <div class="box-link">
        <a href="{{ map.url }}"><img src="{{ map.logo }}"></a>
        <br/>
        <p class="btn"><a href="{{ map.url }}">{{ map.title }}</a></p>
    </div>
	{% endfor %}
</section>
