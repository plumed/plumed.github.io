PLUMED Masterclass
------------------

**WARNING: This page is a draft**

PLUMED Masterclass is a series of virtual and interactive lectures, each one
focused on a specific theme ranging from basic concepts to advanced topics in molecular simulations.
Each class is composed by two lessons: 
* Lesson I: an overview of the methodological background followed by a brief description of the exercises assigned to the students;
* Lesson II: a practical lecture in which the instructor solves the assigned exercises.

In between the two lessons the participants will have one week to complete the exercises on their own or in groups.
 
__Topics__

{:#browse-table .display}
| Lecture | Topic | Date | Time | Instructor |
|:--------:|:--------:|:---------:|:---------:|:---------:|
{% for item in site.data.masterclass %}| {{ item.id }} | {{ item.topic }} | {{ item.date }} | {{ item.time }} | {{ item.instructor }} |
{% endfor %}


__Practical info__

Lessons will take place at **XX:XX** CET. The first lesson of each class will last approximately 1 hour, whereas the correction should last about 2 hours.
The lectures of this first series will be delivered by PLUMED developers.

__Resources__

Participants are expected to run the exercises using their computing resources. For most of the classes,
a laptop with Linux or MacOS will be sufficient. However, for some classes access to a reasonable workstation will be required.
The required software will be provided on a [conda channel](https://anaconda.org/plumed).

Participants will have access to a dedicated [Slack](https://slack.com/) organization, where they will be able to
interact with lecturers and with other participants during the week. Presentations will be done over [Zoom](https://zoom.us/).
The number of participants will be kept low so as to favor interactions.

__How to apply__

Work in progress

<script>
$(document).ready(function() {
var table = $('#browse-table').DataTable({
  "dom": '<"search"f><"top"il>rt<"bottom"Bp><"clear">',
  language: { search: '', searchPlaceholder: "Search lecture..." },
  buttons: [
        'copy', 'excel', 'pdf'
  ],
  "order": [[ 0, "desc" ]]
  });
$('#browse-table-searchbar').keyup(function () {
  table.search( this.value ).draw();
  });
});
</script>
