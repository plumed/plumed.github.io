Thanks!
-----------------------------

PLUMED is largely funded through the time of its [developers and contributors](/people) and the institutions/fellowships paying their salaries.

The following grants/institutions are also acknowledged:

__PLUMED events__

| Title | Location | Date | Organizers | Participants | Description | Link | Funding |
|:--------:|:--------:|:--------:|:---------:|:---------:|:---------:|:---------:|:---------:|
{% for item in site.data.funding %}| {{ item.title }} | {{ item.location }} | {{ item.date }} | {{ item.organisers }} | {{ item.participants }} | {{ item.description }} | [click here]({{ item.link }}) | {{ item.funding }} |
{% endfor %}

__Other grants__

- PNRR and, specifically, the National Center in High Performance Computing, Big Data, and Quantum Computing for funding the development of PLUMED.
