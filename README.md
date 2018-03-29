# Circuit_Notebooks

The repository contains iPython notebooks with all the supporting files to run them.

1. Python libraries needed to run the notebooks:
   * glob, h5py, numpy, pylab, scipy, functools
   * openfermion, openfermionprojectq, openfermionpsi4 ([Github repository](https://github.com/quantumlib/OpenFermion))
   * projectq ([ProjectQ repository](https://projectq.ch))
   
   * For the Rigetti Forest framework and Notebook, one also needs to install
     * pyQuil ([See Documentation](http://pyquil.readthedocs.io/en/latest/start.html))
     * forestopenfermion for OpenFermion interface ([Github repository](https://github.com/rigetticomputing/forestopenfermion))
     * Grove with a set of quantum algorithms ([See Documentation](http://grove-docs.readthedocs.io/en/latest/index.html))
     
2. Notebooks:
   * Run_Ethylene-4-qubit.ipynb - 4 qubit quantum chemistry example with OpenFermion and ProjectQ
   * Run_Ethylene-4-qubit.ipynb - 4 qubit quantum chemistry example with OpenFermion and Forest/pyQuil from Rigetti
   * Run_Ethylene-8-qubit.ipynb - 8 qubit quantum chemistry example with OpenFermion and ProjectQ
   * Nuclear.ipynb - 2-8 qubit nuclear model from the ([ORNL paper](https://arxiv.org/pdf/1801.03897v1.pdf))
   

