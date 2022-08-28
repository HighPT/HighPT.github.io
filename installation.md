---
layout: default
katex: true
---

# Installing the `HighPT` package

`HighPT` can be easily installed in one of two ways:

* **Option 1 -- automatic installation:**  
The simplest way to download and install the latest release of `HighPT` is to run the following command in a `Mathematica` session:
<br><br>
```wl
Import["https://github.com/HighPT/HighPT/raw/master/install.m"]
```
This will download and install `HighPT` in the Applications folder of `Mathematica`'s base directory. 

* **Option 2 -- manual installation**:
Alternatively you can also download the package manually from the GitHub [repository](https://github.com/HighPT/HighPT) and save it in the directory of your choice. In this case the path to the directory containing the `HighPT` code must be specified every time before loading the package by:
<br><br>
```wl
PrependTo[$Path,"path/to/HighPT/directory"]
```
Here `"path/to/HighPT/directory"` corresponds to the path to the directory where the `HighPT` package is saved.
Older versions of the code can be downloaded from [here](https://github.com/HighPT/HighPT/releases) and installed in the same way.

## Loading

After installation, the `HighPT` package can be loaded in any `Mathematica` notebook with the command:
```wl
<< HighPT`
```

If you are new to `HighPT`, you can find information on all routines of the code in the [documentation](./documentation.html), the [example notebooks](https://github.com/HighPT/HighPT/tree/master/example_notebooks), and in the reference article [\[arXiv:2207.10756\]](http://arxiv.org/abs/2207.10756).
