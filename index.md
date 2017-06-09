PLUMED is an open source library for free energy calculations in molecular systems which works together with some of the most popular molecular dynamics engines. Free energy calculations can be performed as a function of many order parameters with a particular  focus on biological problems, using state of the art methods such as metadynamics, umbrella sampling and Jarzynski-equation based steered MD. The software, written in C++, can be easily interfaced with both fortran and C/C++ codes.

PLUMED is free software! To get the download it here or from GitHub.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

