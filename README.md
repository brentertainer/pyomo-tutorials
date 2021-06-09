# Pyomo Examples

This repository contains variety of examples of math programming models implemented primarily with
the *Py*thon *O*ptimization *M*odeling *O*bjects package and written into Jupyter notebooks. A few
examples also compare and contrast `pyomo`-based development with `gurobipy`-based development.

## Recorded Tutorials

I am an active member of the
[INFORMS student chapter at the University of Texas at Austin](https://connect.informs.org/universityoftexasaustin/home).
In that capacity, I have so far led two tutorials using examples from this repository. Recordings
of those tutorials are hosted on YouTube at the links below.
- [Basic Development with Pyomo and Gurobipy](https://youtu.be/pxCogCylmKs)
- [Models on Graphs and Block-Based Implementations](https://youtu.be/T5LjmbyA1o0)

## Software Version

Python has taken the data science world by storm but sometimes understanding what all packages and
which versions are required to run a piece of code can be frustrating. Thankfully, we have
companies like Anaconda, Inc. (headquartered in downtown Austin, TX!) making software versioning
easy with tools like Anaconda. I have built and tested a conda environment
using Anaconda 4.10.1 and exported it to [this yaml file](environment.yaml). The Anaconda
environment may be built from file and activated as follows.
```
conda env create -f environment.yaml
conda activate pyomo-examples
```
I have only tested this on Fedora 34 with x86\_64 architecture. I do not guarantee that this
environment will work across all operating systems and architectures, but it should at the very
least serve as a basis for support to get these codes working on your system.
