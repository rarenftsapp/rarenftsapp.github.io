---
layout: page
title: Pokemons - Generation 5
permalink: /pokemons-gen-5/
parent: Pokemons
---

## Pokemon collection


### Generation 5

<table>
<colgroup>
<col width="20%" />
<col width="10%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Pokemon</th>
<th>ENS link</th>
</tr>
</thead>
<tbody>
{% for pokemon in site.data.pokemons %} 
{% if pokemon.generation == 5 %}
<tr>
<td markdown="span">{{ pokemon.name }}</td>
<td markdown="span"><a href="https://ens.vision/name/{{ pokemon.name }}"> Link </a></td>
</tr>
{% endif %}
{% endfor %}
</tbody>
</table>

