How to get PLUMED
-----------------------------
PLUMED is free and licensed under the [Lesser GNU General Public License](http://www.gnu.org/licenses/lgpl-3.0.en.html).
New and old releases can be downloaded here:

__Recent releases__
{% for item in site.data.releases.current %}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }})
{% endfor %}

__Development version__
* Development version is on [GitHub](http://github.com/plumed/plumed2)

__Previous releases (unsupported)__
{% for item in site.data.releases.old %}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }})
{% endfor %}* [v1.3](https://github.com/plumed/old-releases/blob/master/PLUMED-1.3.0.tgz)
* All releases of the 2.x series can be found [at this link](https://github.com/plumed/plumed2/releases)
* All releases of the 1.x series can be found [at this link](https://github.com/plumed/old-releases)
