# vagrant-mtools

Install a few mongodb tools in a vagrant box

## Installed Tools

- [mtools](https://github.com/rueckstiess/mtools)
  - [mlogfilter](https://github.com/rueckstiess/mtools/wiki/mlogfilter)
  - [mloginfo](https://github.com/rueckstiess/mtools/wiki/mloginfo)
  - [mplotqueries](https://github.com/rueckstiess/mtools/wiki/mplotqueries)
  - [mlogvis](https://github.com/rueckstiess/mtools/wiki/mlogvis)
  - [mlaunch](https://github.com/rueckstiess/mtools/wiki/mlaunch)
- [dex](https://github.com/mongolab/dex)
  - [dex usage](https://github.com/mongolab/dex#usage)

## Requirements

- [vagrant](http://vagrantup.com)

## Installation

```bash
vagrant up
vagrant ssh
```

NOTE: the initial `vagrant up` will take a little bit of time. Once SSH'd into the
box, you have access to all the "Installed Tools" listed above.

