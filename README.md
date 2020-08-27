About gwcs
==========

Home: https://gwcs.readthedocs.io/en/latest/

Package license: BSD 3-clause

Feedstock license: BSD-3-Clause

Summary: Generalized World Coordinate System

GWCS takes a general approach to WCS. It supports a data model which
includes the entire transformation pipeline from input coordinates
(detector by default) to world coordinates. Transformations can be
chained, joined or combined with arithmetic operators using the flexible
framework of compound models in astropy modeling. In the case of a
celestial output frame coordinates provides further transformations
between standard coordinate frames. Spectral output coordinates are
instances of astropy Quantity and are transformed to other units with the
tools in that package.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=214&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/gwcs-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gwcs-green.svg)](https://anaconda.org/nsls2forge/gwcs) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/gwcs.svg)](https://anaconda.org/nsls2forge/gwcs) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/gwcs.svg)](https://anaconda.org/nsls2forge/gwcs) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/gwcs.svg)](https://anaconda.org/nsls2forge/gwcs) |

Installing gwcs
===============

Installing `gwcs` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `gwcs` can be installed with:

```
conda install gwcs
```

It is possible to list all of the versions of `gwcs` available on your platform with:

```
conda search gwcs --channel nsls2forge
```




Updating gwcs-feedstock
=======================

If you would like to improve the gwcs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/gwcs-feedstock are
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


