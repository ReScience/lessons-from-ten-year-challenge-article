# Ten-year reproducibility: lessons from the past to make computational science future-proof

## Abstract

In 2019, the journal ReScience C challenged computational scientists to reproduce computational results that they published themselves ten years or more earlier, and report on the process. Here we draw conclusions from the 28 reproducibility reports that were submitted. Which were the biggest obstacles? Which tools and working habits turned out to best support longevity? What can you do today to increase the chances of your work standing the test of time?

## Introduction

Why should we care about ten-year reproducibility?

Summary of the challenge.

## Obstacles

A discussion of the obstacles that participants encountered.

- code/data preservation
- preservation of the computational protocol
- description of the computational environment
- reconstruction of the computational environnment

## Software tools

The software tools that were involved in the computations to be reproduced, with comments about their positive or negative impact on reproducibility.

- programming languages
- libraries
- operating systems
- build tools (Make etc.)
- version control systems
- data management systems

## Guidelines for future-proof computational science

Warning: this list is drafted from memory. Must be checked against the actual submitted reports!

1. Version control and archiving prevent loss of code and data

2. A fully automated build procedure helps with preserving all the details

3. Specifications with multiple implementations are more stable than code without specifications

C/C++/Fortran vs. Python/R

4. Ecosystems' attitudes towards stability matter

Linux/Mathematica vs. Python

5. Fully reproducible computational environments are useful

Guix

## Conclusions

Discuss some of today's popular technology in view of the above guidelines.

- the SciPy ecosystem
- notebooks
- Web apps
- Git, GitHub, Software Heritage
