title: download
template: default.jade

**vroom** is currently under *heavy* development. There is no stable release.
The easiest (and recommended) method for installing **vroom** is to install 
it from the debain repository (see below).

## ubuntu/debian systems

Add the following line to your `/etc/apt/sources.list` file.

```bash
deb http://iviz.csc.ucdavis.edu/repos/apt/ubuntu oneiric main
```

Download and install the repository key.

```bash
wget -O - http://iviz.csc.ucdavis.edu/repos/apt/iviz.gpg.key | sudo apt-key add -
```

Update APT and install the vroom package.

```bash
sudo apt-get update
sudo apt-get install vroom
```

## installing from source

The source for the project can be
downloaded from [github](https://github.com/jvan/vroom). If installing from
source you will need to install and compile a number of other packages (see
the README file).
