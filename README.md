# robosym-template

Latex template for Robotics Symposia

### 1. Prerequisities

```bash
# only for ubuntu 12.04
$ sudo apt-add-repository ppa:texlive-backports/ppa
$ sudo apt-get update
```

### 2. Edit LaTeX files

### 3. Make pdf

```bash
$ make
```

### Optional. Convert Japanese punctuations

```bash
$ make pub
# or
$ make publish
# will convert $B!V!"!W!V!#!W(B to $B!V!$!W!V!%!W(B in *.tex
# Original files are backed up as *.tex.orig
```

### Optional. cleaning

```bash
$ make clean
# or
$ make wipe
```
