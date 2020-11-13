# This is a page about calculus

1. Section 1.1, Problem 1  <details> Hola que tal</details>
2. Section 1.1, Problem 2  
This was easy, $$2+2 = X$$
3. Section 1.1, Problem 3  <details>
  This is a much longer thing
  
  $$\int_0^1 xdx = \frac{1}{2}$$
</details>

<ul>
{% for member in site.data.test %}
  <li>
      <details>
      <summary>	{{member.name}} </summary>
	{{member.content}}
      </details>
  </li>
{% endfor %}
</ul>

