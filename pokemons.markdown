---
layout: page
title: Pokemons
permalink: /pokemons/
---

## Pokemon collection


<table>
<colgroup>
<col width="20%" />
<col width="10%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Pokemon</th>
<th>Generation</th>
<th>ENS link</th>
</tr>
</thead>
<tbody>
{% for pokemon in site.data.pokemons %} 
<tr>
<td markdown="span">{{ pokemon.name }}</td>
<td markdown="span">{{ pokemon.generation }}</td>
<td markdown="span"><a href="https://ens.vision/name/{{ pokemon.name }}"> Link </a></td>
</tr>
{% endfor %}
</tbody>
</table>
