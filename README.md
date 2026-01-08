About python-lzf-feedstock
==========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/python-lzf-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/FledgeXu/python-neo-lzf

Package license: BSD-3-Clause

Summary: C Extension for liblzf

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=23035&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-lzf-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=23035&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-lzf-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=23035&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-lzf-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=23035&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/python-lzf-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--lzf-green.svg)](https://anaconda.org/conda-forge/python-lzf) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/python-lzf.svg)](https://anaconda.org/conda-forge/python-lzf) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/python-lzf.svg)](https://anaconda.org/conda-forge/python-lzf) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/python-lzf.svg)](https://anaconda.org/conda-forge/python-lzf) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--neo--lzf-green.svg)](https://anaconda.org/conda-forge/python-neo-lzf) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/python-neo-lzf.svg)](https://anaconda.org/conda-forge/python-neo-lzf) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/python-neo-lzf.svg)](https://anaconda.org/conda-forge/python-neo-lzf) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/python-neo-lzf.svg)](https://anaconda.org/conda-forge/python-neo-lzf) |

Installing python-lzf
=====================

Installing `python-lzf` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `python-lzf, python-neo-lzf` can be installed with `conda`:

```
conda install python-lzf python-neo-lzf
```

or with `mamba`:

```
mamba install python-lzf python-neo-lzf
```

It is possible to list all of the versions of `python-lzf` available on your platform with `conda`:

```
conda search python-lzf --channel conda-forge
```

or with `mamba`:

```
mamba search python-lzf --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search python-lzf --channel conda-forge

# List packages depending on `python-lzf`:
mamba repoquery whoneeds python-lzf --channel conda-forge

# List dependencies of `python-lzf`:
mamba repoquery depends python-lzf --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating python-lzf-feedstock
=============================

If you would like to improve the python-lzf recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/python-lzf-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@tetov](https://github.com/tetov/)

