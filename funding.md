Thanks!
-----------------------------

PLUMED is largely funded through the time of its [developers and contributors](/people) and the institutions/fellowships paying their salaries.

The following grants/institutions are also acknowledged:

__PLUMED events__

{% for item in site.data.funding %}
- [{{ item.title }}]({{ item.link }}), held in {{ item.location }} on {{ item.date }}. The event was organized by {{ item.organisers }} and was attended by {{ item.participants }} participants. Description: {{ item.description }} Funding agencies: {{ item.funding }}.
{% endfor %}

__Other grants__

- PNRR and, specifically, the National Center in High Performance Computing, Big Data, and Quantum Computing for funding the development of PLUMED.
