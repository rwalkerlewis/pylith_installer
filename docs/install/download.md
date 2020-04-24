# 1. Download the installer

## Download the installer from the CIG website.

  [pylith-installer-{{ site.installer-version }}.tgz](https://geodynamics.org/cig/software/pylith/pylith-installer-{{ site.installer-version }}.tgz)

  We assume the tarball `pylith-installer-{{ site.installer-version }}.tgz` is downloaded to `$HOME/Downloads`. We will place the installer source code in the directory `$HOME/src/pylith`.

## Unpack the installer source code:

```[bash]
$ mkdir -p $HOME/src/pylith
$ cd $HOME/src/pylith
$ mv $HOME/Downloads/pylith-installer-{{ site.installer-version }}.tgz $HOME/src/pylith/
$ tar -xf pylith-installer-{{ site.installer-version }}.tgz
```