# ortep

This is a re-hosting of the ORTEP software originally found at [ORNL](http://web.ornl.gov/sci/ortep/ortep.html). The newly hosted website is located [here](https://ornl-ndav.github.io/ortep/ortep.html).

# Building And Installation

## Linux

1. Install `gfortran` and `pgplot`
2. `make`
3. `./ortep3`

## macOS

### MacPorts

Install ortep3 including documentation and examples using MacPorts:
1. Install [XCode](https://developer.apple.com/xcode/) and [MacPorts](https://www.macports.org/)
2. command line installation
```
$ sudo port install ortep3

```

### Homebrew

1. Install [XCode](https://developer.apple.com/xcode/), [XQuartz](https://www.xquartz.org/) and [Homebrew](https://brew.sh/)
2. command line build:
```
$ brew install gcc
$ brew install homebrew/x11/pgplot
$ make
$ ./ortep3
```

# Windows

A graphical user interface (GUI) can be found as part of the [WinGX software](http://www.chem.gla.ac.uk/~louis/software/ortep/index.html).
