About ffnvcodec-headers
=======================

Home: https://git.videolan.org/?p=ffmpeg/nv-codec-headers.gi

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: FFmpeg version of headers required to interface with Nvidias codec APIs

FFmpeg version of headers required to interface with Nvidias codec APIs.

Corresponds to Video Codec SDK version 8.2.25.

Minimum required driver versions:
Linux: 396.24 or newer
Windows: 397.93 or newer


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/ffnvcodec-headers-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/ffnvcodec-headers-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ffnvcodec--headers-green.svg)](https://anaconda.org/loopbio/ffnvcodec-headers) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/ffnvcodec-headers.svg)](https://anaconda.org/loopbio/ffnvcodec-headers) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/ffnvcodec-headers.svg)](https://anaconda.org/loopbio/ffnvcodec-headers) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/ffnvcodec-headers.svg)](https://anaconda.org/loopbio/ffnvcodec-headers) |

Installing ffnvcodec-headers
============================

Installing `ffnvcodec-headers` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `ffnvcodec-headers` can be installed with:

```
conda install ffnvcodec-headers
```

It is possible to list all of the versions of `ffnvcodec-headers` available on your platform with:

```
conda search ffnvcodec-headers --channel loopbio
```




Updating ffnvcodec-headers-feedstock
====================================

If you would like to improve the ffnvcodec-headers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/ffnvcodec-headers-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.