---
# the default layout is 'page'
# icon: fas fa-info-circle
title: équipe
order: 1
# layout: people
lang: fr
page_id: team
permalink: /équipe/
---


<div id="container">
<div class="container page">
<main role="main">

{% assign members = site.data.people | values
                                     | where_exp:"item", "item.active and item.hidden != true"
                                     | sort: "title"
                                     | last_name_sort: "name" %}


<div class="container-fluid">
<div class="row">
{% for person in members %}
    {% include standard_person_card.md person=person %}
{% endfor %}
</div>
</div>


</main>
</div>
</div>