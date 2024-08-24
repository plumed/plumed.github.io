Thanks!
-----------------------------

PLUMED is largely funded through the time of its [developers and contributors](/people) and the institutions/fellowships paying their salaries.
In particular, we would like to acknowledge the institutions of the PLUMED core developers:
* [Institut Pasteur](https://www.pasteur.fr/en) and [CNRS](https://www.cnrs.fr/en), France
* [International School for Advanced Studies](https://www.sissa.it), Italy
* [University of Milan](https://www.unimi.it/en), Italy
* [Queen's University Belfast](https://www.qub.ac.uk), UK

The following grants, institutions, and companies are also acknowledged for their support to PLUMED events and software development over the years.

__PLUMED events__

{% for item in site.data.funding %}
- [{{ item.title }}]({{ item.link }}), held in {{ item.location }} on {{ item.date }}. The event was organized by {{ item.organisers }} and was attended by {{ item.participants }} participants. Description: {{ item.description }} Funding agencies: {{ item.funding }}.
{% endfor %}

__PLUMED development__

- PNRR and, specifically, the National Center in High Performance Computing, Big Data, and Quantum Computing for funding the development of PLUMED.
