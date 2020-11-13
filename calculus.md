# Test set


<ul>
{% for member in site.data.calculus %}
  <li>
      <details>
      <summary>	Section {{member.section}}, Problem {{member.number}} </summary>
	{{member.content}}
      </details>
  </li>
{% endfor %}
</ul>

