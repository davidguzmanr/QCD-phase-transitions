# QCD phase transitions

![Julia 1.3](https://img.shields.io/badge/Julia-1.3-green)

Routine to solve the system of integro-differential equations in Julia 1.3.

> **A first approach to the study ofthe QCD phase transition in cosmology**<br>
> Aldo Gamboa <sup>1</sup>, David Guzmán<sup>1</sup>, Victor Knapp<sup>1</sup>, José Padua<sup>1,2</sup>, Saúl Ramos-Sánchez <sup>2,3</sup><br>
> <sup>1</sup>Facultad de Ciencias, Universidad Nacional Autónoma de México, <sup>2</sup>Instituto de Física, Universidad Nacional Autónoma de México, <sup>3</sup>Physik Department T75, Technische Universität München<br>
>
> <p align="justify"><b>Abstract:</b> <i>The cosmological QCD confinement is studied as a first order phase transition with the MIT bag model. The basic concepts of cosmology, phase transitions, nucleation theory are introduced. The equations of the dynamics of the transition are established and a program is supplied for the numerical solution. The solution of the dynamics of the transition are studied varying the surface tension of the bubble, the critical temperature and the number of dynamical quarks for current limits. The objective of this article is to introduce the basics of the cosmological QCD phase transition for an advanced undergraduate or graduate student.</i></p>

## Project members ##

* Aldo Gamboa, Universidad Nacional Autónoma de México
* David Guzmán, Universidad Nacional Autónoma de México
* Victor Knapp, Universidad Nacional Autónoma de México
* José Padua, Universidad Nacional Autónoma de México
* [Saúl Ramos-Sánchez](https://www.fisica.unam.mx/es/personal.php?id=398), Universidad Nacional Autónoma de México, Technische Universität München


## Getting started ##

To download Julia go to [The Julia Programming Language](https://julialang.org/downloads/). You will also need Jupyter to run the notebook, install [Anaconda](https://www.anaconda.com/distribution/) to get it. After that you will also need the Julia kernel for Jupyter, open Julia and type

```
using Pkg
Pkg.add("IJulia")
```
Then clone the repository (or download the zip)

```
git clone https://github.com/davidguzmanr/QCD-phase-transitions.git
```

Open the Jupyter notebook and run the notebook, you can change the different constants at the beginning, the whole routine can take several hours before it reaches h = 1. 
