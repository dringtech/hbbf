---
layout: page
permalink: /vip/
---
# Love, Hebden

![](/images/love-Hebden-card.png)

<table class="biz-list">
<thead> <th>Business</th> <th class='offer'>Offer</th> <th>Terms</th> </thead>
<tbody>
{% for b in site.data.vipbusinesses %}
<tr><td>{{ b.business }}</td><td class='offer'>{{ b.offer }}</td><td>{{ b.terms }}</td></tr>
{% endfor %}
</tbody>
</table>
