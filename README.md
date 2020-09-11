About _current_repodata_hack
============================

Home: https://github.com/conda-forge/_current_repodata_hack-feedstock

Package license: LicenseRef-OTHER

Feedstock license: BSD-3-Clause

Summary: Meta-package to fix current_repodata

As of writing, conda-forge has versions of the linux compilers that are ahead of the
ones in the global pinnings. The current_repodata.json file only pulls in the latest
version of a package by default. Thus anytime one asks for the compilers in the pinnings,
the solver will always fail on current_repodata.json and have to pull all of the repodata.
The packages here make sure the latest versions of the compilers we use are in
current_repodata.json by depending on those packages. Thus it solves the solver inefficiency.
It also helps in cases when the solver appears to pull older builds of the compilers when they are
not explicitly asked for in the environment.


Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/conda-forge/_current_repodata_hack-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/conda-forge/_current_repodata_hack-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Drone</td>
    <td>
      <a href="https://cloud.drone.io/conda-forge/_current_repodata_hack-feedstock">
        <img alt="linux" src="https://img.shields.io/drone/build/conda-forge/_current_repodata_hack-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10701&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/_current_repodata_hack-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10701&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/_current_repodata_hack-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10701&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/_current_repodata_hack-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=10701&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/_current_repodata_hack-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_64_75-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_75) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_75) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_75) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_75) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_64_84-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_84) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_84) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_84) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_64_84) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_aarch64_75-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_75) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_aarch64_84-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_aarch64_84) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_ppc64le_75-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_75) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_current_repodata_hack_gcc_linux_ppc64le_84-green.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84.svg)](https://anaconda.org/conda-forge/_current_repodata_hack_gcc_linux_ppc64le_84) |

Installing _current_repodata_hack
=================================

Installing `_current_repodata_hack` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `_current_repodata_hack_gcc_linux_64_75, _current_repodata_hack_gcc_linux_64_84, _current_repodata_hack_gcc_linux_aarch64_75, _current_repodata_hack_gcc_linux_aarch64_84, _current_repodata_hack_gcc_linux_ppc64le_75, _current_repodata_hack_gcc_linux_ppc64le_84` can be installed with:

```
conda install _current_repodata_hack_gcc_linux_64_75 _current_repodata_hack_gcc_linux_64_84 _current_repodata_hack_gcc_linux_aarch64_75 _current_repodata_hack_gcc_linux_aarch64_84 _current_repodata_hack_gcc_linux_ppc64le_75 _current_repodata_hack_gcc_linux_ppc64le_84
```

It is possible to list all of the versions of `_current_repodata_hack_gcc_linux_64_75` available on your platform with:

```
conda search _current_repodata_hack_gcc_linux_64_75 --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating _current_repodata_hack-feedstock
=========================================

If you would like to improve the _current_repodata_hack recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/_current_repodata_hack-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@isuruf](https://github.com/isuruf/)

