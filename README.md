# Python-based Atomistic Spin Dynamics simulator (pyASD)


This is a python package containing
some tools for spin dynamics simulations
By Shunhong Zhang (USTC)
Copyright reserved 2023
szhang2@ustc.edu.cn


## Code distributions:

* core: core scripts for spin dynamics simulations
* utility: scripts for post-processing, applied to the current code and Spirit
* data_base: some exchange parameters for typical magnetic materials, udner construction
* examples: some examples to do fast test on the code
* tests_basic: some testing cases

## Installation
* Run the script
./compile.sh

* To check whether you have successfully install the package, go to the python interactive shell
 
import asd.core.geometry

import asd.utility.spirit_tool

import data_base.exchange_for_CrI3

If everything runs smoothly then it should be done.

* If it does not work, try one of the following:
 python setup.py install --home=.
 
 python setup.py install --user
 If you still have problems, contact the author for help
 

## To clean the package:
./clean
this operation will remove:
build and dists, which are generated upon compilation
results in the test directory, including dat/ovf files and figures

