# ThinFilm_calculation
C++ code to perform calculation of the optical properties of thin films.

## Motivation
The goal is to create a C++ library that is capable of calculating reflection, transmission, absorption and ellipsometric 
parameters (tg(Psi) and cos(Delta)) of any given multilayer thin film stack, including stacks that consist of periodically repeating layers.

## Applicability
The code can be used by people who design various types of optical coatings, like anti-reflection coatings, mirrors, beamsplitters, etc. 
In addition it may be usefull to
those, who analyze/simulate ellipsometric data.

## Current structure
The projects contains two files:
* multilayer.h
* multilayer.cpp

## Building the project
* clone the repository to yor own project
* include **multilayer.h** in you project

## Examples of usage
More information on the code and examples of its usage can be found in the **Manual.pdf** in the **docs** folder.  
In addition, the code (without the support of periodically repeating layers) is implemented in the Opal software, that can be found under https://github.com/mbiednov/opal/releases