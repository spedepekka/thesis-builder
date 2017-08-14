
# Thesis builder

Ubuntu + Virtualbox + Vagrant + Ansible + LaTex

This project creates a Ubuntu box which can build my Master's thesis pdf from LaTex sources.

## Notes

This project mounts `../doc` to VM box, because it is meant to be used as a submodule for my thesis repository.

## Setup

This is the setup I've used

* OS X El Capitan
* Vagrant 1.7.4
* Virtualbox 5.0.10
* Ansible 2.0.0.2

## Watch

```
vagrant ssh
cd doc
gulp watch
```

