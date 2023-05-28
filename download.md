How to get PLUMED
-----------------------------
PLUMED is free and licensed under the [Lesser GNU General Public License](http://www.gnu.org/licenses/lgpl-3.0.en.html).
New and old releases can be downloaded here:

__Recent releases__
{% for item in site.data.releases.current %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }}) ([CHANGES](https://plumed.github.io/doc-v{{ vers }}/user-doc/html/_c_h_a_n_g_e_s-2-{{ ver[1] }}.html))
{% endfor %}

__Development version__
* Master branch on [GitHub](http://github.com/plumed/plumed2)
{% if site.data.releases.beta %}* Beta release [v{{ site.data.releases.beta }}](https://github.com/plumed/plumed2/releases/tag/v{{ site.data.releases.beta }}) {% endif %}

__Previous releases (unsupported)__
{% for item in site.data.releases.old %}{% assign ver=item | split: '.'%}{% assign vers=ver[0] |append: '.' |append: ver[1]%}* [v{{ item }}](https://github.com/plumed/plumed2/releases/tag/v{{ item }}) ([CHANGES](https://plumed.github.io/doc-v{{ vers }}/user-doc/html/_c_h_a_n_g_e_s-2-{{ ver[1] }}.html))
{% endfor %}* [v1.3](https://github.com/plumed/old-releases/blob/master/PLUMED-1.3.0.tgz)
* All releases of the 2.x series can be found [at this link](https://github.com/plumed/plumed2/releases)
* All releases of the 1.x series can be found [at this link](https://github.com/plumed/old-releases)

__Packages__

PLUMED is also available as a package in a few binary or source distributions. Some of these packages are activiely maintained by PLUMED developers:
* [MacPorts](https://www.macports.org/), ports [plumed](https://ports.macports.org/port/plumed) and [py-plumed](https://ports.macports.org/port/py-plumed), both as a pre-compiled binary (with basic capabilities) and source code (with more MPI and compiler options and including optional modules). Port [plumed-devel](https://ports.macports.org/port/plumed-devel) provides a snapshot of the current development version.
* [Conda-forge](https://conda-forge.org/), packages [plumed](https://anaconda.org/conda-forge/plumed) and [py-plumed](https://anaconda.org/conda-forge/py-plumed), as pre-compiled binaries with basic capabilities. Other conda binaries containing development versions or nightly builds are available on the [plumed channel](https://anaconda.org/plumed).
* Python wrappers are also available on [PyPI](https://pypi.org/), package [plumed](https://pypi.org/project/plumed/). If you download these wrappers, you will have to install the PLUMED library separately.

Other packages are contributed and maintained by the community (please let us know if a package or repository is missing here):
* [Arch-linux](https://aur.archlinux.org/), packages [plumed](https://aur.archlinux.org/packages/plumed) and [plumed-mpi](https://aur.archlinux.org/packages/plumed-mpi).
* [DPorts](https://github.com/DragonFlyBSD/DPorts), package [plumed](https://github.com/DragonFlyBSD/DPorts/tree/master/science/plumed).
* [Free-BSD ports](https://www.freebsd.org/ports/), package [plumed](https://www.freshports.org/science/plumed).
* [NixOS packages](https://github.com/NixOS) (unstable), package [plumed](https://github.com/NixOS/nixpkgs/blob/nixos-unstable/pkgs/development/libraries/science/chemistry/plumed/default.nix).
* [Pkgsrc](https://www.pkgsrc.org/), package [plumed](https://pkgsrc.se/math/plumed).
* [SlackBuilds](https://slackbuilds.org/), package [plumed](https://slackbuilds.org/repository/15.0/libraries/PLUMED/).
* [Spack](https://spack.io/), package [plumed](https://spack.github.io/packages/package.html?name=plumed).
