# BU Computational Research Intro


## General Getting Started

Research Computing Services Tutorials: https://www.bu.edu/tech/about/training/classroom/rcs-tutorials/ -- either attend in person, or complete on your own with provided materials. In particular, the following are highly recommended dpending on prior experience:
* Introduction to Linux
* Introduction to BU's Shared Computing Cluster
* Intermediate Usage of the SCC (**most highly recommended**)
* Introduction to Python

BU Shared Computing Cluster Access:
* Enrolling in these courses will give you a temporary account. 
* Alternatively you can ask your Advisor to add you as a temporary member to their Projects

Other Potentially Helpful Resources:
* BU SCC Online Resource: https://www.bu.edu/tech/support/research/system-usage/
* Linux command line cheat sheet: https://cheatography.com/davechild/cheat-sheets/linux-command-line/
* Anaconda: https://www.anaconda.com/
* Docker: https://www.docker.com/
* GitHub: https://docs.github.com/en
* VSCode: https://code.visualstudio.com/

## Lejeune Lab Specific Information

### First "Assignment"
During a rotation with the Lejeune Lab, the first thing you will do is figure out how to run FEniCS (either install in on your local computer or run it on the SCC) and run a tutorial example of your choosing. Once you have the tutorial running smoothly and understand what each line of code in the tutorial is doing we will meet and discuss next steps. Typically, this should be done in about 1 week.

### Recommended BU Courses
* `ENG ME 521`: Continuum Mechanics 
* `ENG ME 538`: Introduction to Finite Element Methods and Analysis
* `ENG ME 580`: Theory of Elasticity
* `ENG EC 503`: Introduction to Learning from Data (More advanced) or `CAS CS 542`: Machine Learning (General introduction)

### Recommended Online Courses and Resources
* Finite Element Analysis: https://www.coursera.org/learn/finite-element-method
* Continuum Physics: https://open.umich.edu/find/open-educational-resources/engineering/lectures-continuum-physics
* Advanced Elasticity: https://imechanica.org/node/725
* Machine Learning: https://cs229.stanford.edu/
* Deep Learning for Computer Vision: http://cs231n.stanford.edu/
* Pytorch Tutorials: https://pytorch.org/tutorials/
* FILL IN HERE

### Python
Popular packages that we use:
* numpy
* matplotlib
* scipy
* sklearn
* skimage
* FILL IN HERE

### FEniCS
Instructions for using FEniCS on the SCC:
1. Load FEniCS module using the command: 
    
    ```bash 
    module load fenics/2019.1.0 
    ```
2. Run python script with prepended command `run_fenics.sh`, for example 
    
    ``` bash 
    run_fenics.sh python3 my_fenics_script.py
    ```
Instructions for using FEniCS locally:

FILL IN HERE

### GMSH
Instructions for using GMSH on the SCC:

FILL IN HERE

Instructions for using GMSH locally:

FILL IN HERE

### PyTorch
Instructions for using PyTorch on the SCC:

FILL IN HERE

Instructions for using PyTorch locally:

FILL IN HERE
