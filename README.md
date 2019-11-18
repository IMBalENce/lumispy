.. image:: https://travis-ci.org/lumispy/lumispy.svg?branch=master
    :target: https://travis-ci.org/lumispy/lumispy

.. image:: https://coveralls.io/repos/github/lumispy/lumispy/badge.svg?branch=master
    :target: https://coveralls.io/github/lumispy/lumispy?branch=master
    
# LumiSpy

### Introduction

LumiSpy is an extension Python package for multi-dimensional data analysis provided
by the [HyperSpy](http://hyperspy.org) library. It is aimed at helping with luminescence analysis (cathodoluminescence, photoluminescence and electroluminescence).

LumiSpy is released under the GPL v3 license. 

If analysis using pyxem forms a part of published work please consider recognising the code 
development by citing the [github repository](www.github.com/lumispy/lumispy).

### Installation

##### Creating a conda environment

LumiSpy requires Python 3 and conda - we suggest using the Python 3 version of [Miniconda](https://conda.io/miniconda.html).

We recommend creating a new environment for the lumispy package (or installing it in the hyperspy environment, if you have one already). To create a new environment:

1. Load the anaconda prompt

2. Run the following command:

    $ conda create -n lumispy

##### Installing the package in the new environment

Now that you have created a new environment, install the package:

1. Download the [source code](https://github.com/pyxem/pyxem) and put it in a directory on your computer (by default, GitHub saves it in `Username\Documents\GitHub\lumispy`).

2. Load the anaconda prompt

3. Change current working directory to the folder where you downloaded the source code:
    $ cd PATH_TO_SOURCE_CODE

4. Activate the lumispy environment
    $ conda activate lumispy

5. Install the package running:
    $ pip install . -y

Installation is completed! To start using it, check the next section.

### Getting Started

To get started using lumispy, especially if you are unfamiliar with Python, we recommend using [Jupyter notebooks](https://jupyter.org/). Having installed lumispy as above, a Jupyter notebook can be opened using the following commands entered into an anaconda prompt (from scratch):

    $ conda activate lumispy
    $ jupyter lab

[Tutorials and example workflows](https://github.com/LumiSpy/lumispy/tree/master/lumispy_demos) have been curated as a series of Jupyter notebooks that you can work through and modify to perform many common analyses. Simply:

1. Copy and paste the `lumispy_demos` folder in your desired folder
2. Load lumispy (as shown above)
3. In Jupyter lab, navigate to the folder and start using the notebook