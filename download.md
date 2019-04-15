How to get PLUMED
-----------------------------
PLUMED is free and licensed under the [Lesser GNU General Public License](http://www.gnu.org/licenses/lgpl-3.0.en.html).
New and old releases can be downloaded here:

__Recent releases__
{% for item in site.data.releases.current %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }}) ([CHANGES](https://plumed.github.io/doc-v{{ vers }}/user-doc/html/_change_log.html))
{% endfor %}

__Development version__
* Master branch on [GitHub](http://github.com/plumed/plumed2)
{% if site.data.releases.beta %}* Beta release [v{{ site.data.releases.beta }}](https://github.com/plumed/plumed2/releases/tag/v{{ site.data.releases.beta }}) {% endif %}

__Previous releases (unsupported)__
{% for item in site.data.releases.old %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }}) ([CHANGES](https://plumed.github.io/doc-v{{ vers }}/user-doc/html/{% if ver[1] < 1 %}_c_h_a_n_g_e_s-2-0{% elsif ver[1] < 4 %}_changelog{% else %}_change_log{% endif %}.html))
{% endfor %}* [v1.3](https://github.com/plumed/old-releases/blob/master/PLUMED-1.3.0.tgz)
* All releases of the 2.x series can be found [at this link](https://github.com/plumed/plumed2/releases)
* All releases of the 1.x series can be found [at this link](https://github.com/plumed/old-releases)
