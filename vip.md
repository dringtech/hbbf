---
layout: page
permalink: /vip/
---
# Love, Hebden

<img alt="love, Hebden xx" src="/images/love-Hebden-card.png" class='righty flush-align-top'>
This is the list of businesses participating in the 'love, Hebden xx'
promotion, which was originally created during the Calderdale Rising
crowdfunder.

<table class="biz-list cleary">
<thead> <th>Business</th> <th class='offer'>Offer</th> <th>Terms</th> </thead>
<tbody>
{% for b in site.data.vipbusinesses %}
<tr><td>{{ b.business }}</td><td class='offer'>{{ b.offer }}</td><td>{{ b.terms }}</td></tr>
{% endfor %}
</tbody>
</table>
