The PLUMED manual
------------------------------------
Here you can find the user manuals for currently supported and old versions of PLUMED, along
with a manual of the PLUMED [GitHub](https://github.com/plumed/plumed2) master branch (development version).

__Documentation for recent releases__
* [v2.5.x](http://plumed.github.io/doc-v2.5/user-doc/html/index.html)
* [v2.4.x](http://plumed.github.io/doc-v2.4/user-doc/html/index.html)

__Documentation for development version__
* [Development version](http://plumed.github.io/doc-master/user-doc/html/index.html)

__Documentation for previous, unsupported releases__
* [v2.3.x](http://plumed.github.io/doc-v2.3/user-doc/html/index.html)
* [v2.2.x](http://plumed.github.io/doc-v2.2/user-doc/html/index.html)
* [v2.1.x](http://plumed.github.io/doc-v2.1/user-doc/html/index.html)
* [v2.0.x](http://plumed.github.io/doc-v2.0/user-doc/html/index.html)
* [v1.3 (pdf manual)](/pdf/manual_1-3-0.pdf)

{% for item in LLL %}
{% assign v=item | split: '.'%}
{{ v[0] }}.{{ v[1] }}
* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }})
{% endfor %}

__Documentation for recent releases__
{% for item in site.data.releases.current %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ vers }}.x](http://plumed.github.io/doc-v{{ vers }}/user-doc/html/index.html)
{% endfor %}
