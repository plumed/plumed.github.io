PLUMED Masterclass
------------------

PLUMED Masterclass is a series of virtual and interactive classes, each one
focused on a specific theme ranging from basic concepts to advanced topics in molecular simulations.
Each class is composed by two lectures held on [Zoom](https://zoom.us/): 
* Lecture I: an overview of the methodological background followed by a brief description of the exercises assigned to the students;
* Lecture II: a practical lecture in which the instructor solves the assigned exercises.

In between the two lectures, the participants will have one week to complete the exercises on their own or in groups.
They will have access to a dedicated [Slack](https://slack.com/) organization, where they will be able to
interact with lecturers and with other participants during the entire week.
The number of participants will be kept low so as to favor interactions.
 
__List of Classes__

{:#browse-table .display}
| Class | Topic | Lecture I | Lecture II | Instructor |
|:--------:|:--------:|:---------:|:---------:|:---------:|
{% for item in site.data.masterclass %}| {{ item.id }} | {{ item.topic }} | {{ item.date-I }} | {{ item.date-II }} | {{ item.instructor }} |
{% endfor %}


__Practical info__

All lectures will take place at **7AM** PST / **10AM** EST / **4PM** CET / **10PM** CST. The first lecture of each class will last approximately 1 hour, whereas the correction should last about 2 hours.
The classes of this first series will be delivered by PLUMED developers.

__Resources__

Participants are expected to run the exercises using their computing resources. For most of the classes,
a laptop with Linux or MacOS will be sufficient. However, for some classes access to a reasonable workstation will be required.
The required software will be provided on a [conda channel](https://anaconda.org/plumed).

__How to apply__

If you want to partecipate to one or more classes, please apply [here]().
Due to the limited number of places available, we will let you know in due time (one month before each class? More?) if your application has been accepted.

<script>
$(document).ready(function() {
var table = $('#browse-table').DataTable({
  "dom": '<"search"f><"top"il>rt<"bottom"Bp><"clear">',
  language: { search: '', searchPlaceholder: "Search..." },
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
