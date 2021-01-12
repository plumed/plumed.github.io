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
{% for item in site.data.masterclass %}| {{ item.id }} | [{{ item.topic }}]({{ item.web }}) | [{{ item.date-I }}]({{ item.video-I }}) | [{{ item.date-II }}]({{ item.video-II }}) | [{{ item.instructor }}]({{ item.web-i }}) |
{% endfor %}

By clicking on the **Topic** of each class, you will be redirected to the material used in the corresponding class.
By clicking on **Lecture I** or **Lecture II**, you will be redirected to the live recording of the lecture on YouTube.

__Practical info__

All lectures will take place at **7AM** San Francisco / **10AM** New York / **3PM** London / **4PM** Paris / **10PM** Beijing time. The first lecture of each class will last approximately 1 hour, whereas the correction should last about 2 hours.
The classes of this first series will be delivered by PLUMED developers.

__Poster session__

At the end of each series of lectures, all participants will be invited to a virtual poster session.
More info will be available soon.

__Live vs recorded classes__

All lectures will be recorded and promptly made available for those who could not attend the live classes.
Participants to the live lectures will have the advantage of:
* interacting with the instructors and the other participants on Zoom during the lectures and on Slack during the week between two consecutive lectures;
* attending/presenting their work at the final poster session.

__Resources__

Participants are expected to run the exercises using their computing resources. For most of the classes,
a laptop with Linux or MacOS will be sufficient. However, for some classes access to a reasonable workstation will be required.
The required software will be provided on a [conda channel](https://anaconda.org/plumed).

__How to apply__

If you want to partecipate to one or more classes, **please apply [here](https://forms.gle/MHJyarH4LUcaqjh68) at the latest 2 months before the first class you plan to attend**. 
Due to the limited number of places available, one month before each selected class we will let you know if your application has been accepted. We do not foresee any fee at this time, but we might have to add a small one to cover running costs.

__Participation__

If your application has been accepted, you will receive an invitation to join a Slack workspace one month before Lecture I. Please accept the invitation and join the workspace. The workspace contains a separate private channel for each masterclass (e.g. `masterclass-21-1` will be the channel hosting the first masterclass). If this is not your first masterclass, your user will be added to the relevant channel and you will be notified directly on Slack. Please confirm that you will participate to the classes. We have a long wait list, but we are going to keep the number of live participants to a maximum of 40. A no show at the Zoom lectures will imply a cancellation from future masterclasses so as to free space for another applicant.

<script>
$(document).ready(function() {
var table = $('#browse-table').DataTable({
  "dom": '<"search"f><"top"il>rt<"bottom"Bp><"clear">',
  language: { search: '', searchPlaceholder: "Search..." },
  buttons: [
        'copy', 'excel', 'pdf'
  ],
  "order": [[ 0, "asc" ]]
  });
$('#browse-table-searchbar').keyup(function () {
  table.search( this.value ).draw();
  });
});
</script>
