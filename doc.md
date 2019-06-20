The PLUMED manual
------------------------------------
Here you can find the user manuals for currently supported and old versions of PLUMED, along
with a manual of the PLUMED [GitHub](https://github.com/plumed/plumed2) master branch (development version).

__Documentation for recent releases__
{% for item in site.data.releases.current %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ vers }}.x](http://plumed.github.io/doc-v{{ vers }}/user-doc/html/index.html)
{% endfor %}

__Documentation for development version__
* [Development version](http://plumed.github.io/doc-master/user-doc/html/index.html)

__Documentation for previous, unsupported releases__
{% for item in site.data.releases.old %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ vers }}.x](http://plumed.github.io/doc-v{{ vers }}/user-doc/html/index.html)
{% endfor %}* [v1.3 (pdf manual)](/pdf/manual_1-3-0.pdf)

Further reading
------------------------------------
Here you can find a list of papers containing practical PLUMED tutorials:

* [Barducci A., Pfaendtner J., Bonomi M. (2015) Tackling Sampling Challenges in Biomolecular Simulations. In: Kukol A. (eds) Molecular Modeling of Proteins. Methods in Molecular Biology (Methods and Protocols), vol 1215. Humana Press, New York, NY](https://link.springer.com/protocol/10.1007/978-1-4939-1465-4_8)

