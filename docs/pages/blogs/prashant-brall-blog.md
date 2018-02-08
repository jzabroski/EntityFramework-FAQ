---
permalink: prashant-brall-blog
---

<h2>Prashant Brall's Blog</h2>

<table>
	<tbody>
{% for blog in site.data.blogs %}
	{% if blog.Kind == "PrashantBrall" %}
		<tr>
			<td>
				<h3><a href="{{ blog.Url }}">{{ blog.Title }}</a></h3>
				{{ blog.Description }}
			</td>
		</tr>
	{% endif %}
{% endfor %}
				
	</tbody>
</table>