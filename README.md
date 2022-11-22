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
* `ENG ME 721`: Applied Mathematics in Mechanics
* `ENG EC 503`: Introduction to Learning from Data (More advanced) or `CAS CS 542`: Machine Learning (General introduction)

(**Recommended order**)

First semester:`ENG ME 521`, `ENG ME 538`, `ENG ME 721`

Second semester: `ENG ME 580`, `ENG EC 503` or `CAS CS 542`

### Recommended Online Courses and Resources
* Finite Element Analysis: https://www.coursera.org/learn/finite-element-method
* Continuum Physics: https://open.umich.edu/find/open-educational-resources/engineering/lectures-continuum-physics
* Advanced Elasticity: https://imechanica.org/node/725
* Machine Learning: https://cs229.stanford.edu/ or [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction?utm_source=gg&utm_medium=sem&utm_campaign=07_Machine_Learning_Stanford_Search-US&utm_content=B2C&campaignid=685340575&adgroupid=32639001781&device=c&keyword=machine%20learning%20techniques&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=606802906474&hide_mobile_promo=&gclid=Cj0KCQiAg_KbBhDLARIsANx7wAxZRh6MDeb8VTJtdWNTyiwTonwTS4TRGD7yiviQRIKmJlVrSai6dwIaAjVfEALw_wcB#courses) or [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning?utm_source=gg&utm_medium=sem&utm_campaign=07_Machine_Learning_Stanford_Search-US&utm_content=B2C&campaignid=685340575&adgroupid=32639001781&device=c&keyword=machine%20learning%20techniques&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=606802906474&hide_mobile_promo=&gclid=Cj0KCQiAg_KbBhDLARIsANx7wAxZRh6MDeb8VTJtdWNTyiwTonwTS4TRGD7yiviQRIKmJlVrSai6dwIaAjVfEALw_wcB#courses)

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
    module purge
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

1. Load GMSH and all other necessary modules using the commands: 
    
    ```bash 
    module purge
    module load openmpi/3.1.4_gnu-8.1
    module load python3/3.7.9
    module load gmsh/4.7.1
    ```
2. Run python script with prepended command `python3`, for example 
    
    ``` bash 
    python3 my_gmsh_script.py
    ```

Instructions for using GMSH locally:

The easiest way to use GMSH locally is to set it up using [Anaconda](https://www.anaconda.com/).
1. Create a new enviroment for GMSH in anaconda either using the graphical interface (`Environments` --> `Create` on bottom left).
    Alternatively, you can create and environment using the terminal by running the command: 
    
    ```bash
    conda create --name gmsh-env python=3.9.13
    ```
    
    You can find more information about creating environmets [here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

2. Activate the "gmsh-env" environment by clicking on the green arrow next to the environment name in the graphical interface and select "Open Terminal". Alternatively, you can use the terminal and run the following command:

    ```bash 
    conda activate gmsh-env
    ```
3. Install GMSH in the terminal using the following command:

    ```bash
    conda install -c conda-forge gmsh
    ```

To open GMSH, just type `gmsh` in the terminal with the `gmsh-env` activated.
To run a GMSH python file:

1. Make sure that `gmsh-env` is activated
2. Go to your working directory

```bash
cd \FullPath
```
3. Run the command

```bash 
python3 my_gmsh_script.py
```
### PyTorch
Instructions for using PyTorch on the SCC:

FILL IN HERE

Instructions for using PyTorch locally:

FILL IN HERE
