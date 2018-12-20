---
---
# goodeats

A curated list of places to eat in central Ohio.
{% for place in site.data.places %}

- [{{ place.name }}](#{{ place.name }})

{% endfor %}

{% for place in site.data.places %}

## {{ place.name }}

{% for location in place.locations %}

### [{{ location.name }}]({{ location.website }}) {{ location.emoji }}
[{{ location.address }}](https://maps.google.com/?q={{ location.address }})

{% if location.recommendations %}
#### Recommendations

{% for recommendation in location.recommendations %}

- {{ recommendation }}

{% endfor %}

{% endif %}

{% endfor %}

{% endfor %}