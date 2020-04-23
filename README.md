# PyFigtree
A python wrapper for figtree, a library written here: https://github.com/vmorariu/figtree.  They have a python wrapper, but I found it insufficient for my needs.


I basically just moved the setup.py file and figtree.pyx to the root directory and updated setup.py to build all the .cpp files rather than having to run make  before hand.

Instructions to use:
```
git clone --recurse-submodules https://github.com/mikeswhitney33/PyFigtree
pip install PyFigtree/requirements.txt
python PyFigtree/setup.py build_ext --inplace # or python PyFigtree/setup.py install
```