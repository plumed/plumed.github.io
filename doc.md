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

Need help?
-----------------------------

If you are having problems with installing or using PLUMED that you cannot solve checking the manuals, the tutorials and the masterclasses, please consult our users mailing list [here](https://groups.google.com/forum/#!forum/plumed-users).

A few useful guidelines:

* Before posting, first check if someone has already asked/answered your question!
* If you are posting for the first time, your mail might be moderated. Therefore, it will take a bit of time for your messagge to appear in the group.
* Please, do not post your question twice (or more times)!
