# GDL kernel for IPython/Jupyter

Demo [Notebook](demo.ipynb)

The current version was found to work with pexpect 4.6, jupyter 4.4, and jupyter-notebook 5.7. 

To install:
```
python setup.py install --prefix=~/.local
```
or
```
python3 setup.py install --prefix=~/.local
```

This should make an GDL directory containing the kernelspec in `~/.local/share/jupyter/kernels`, and place `gdl_kernel.py` in `~/.local/lib/pythonX.X/site-packages`.

To run:
```
jupyter notebook 
#Select GDL kernel from dropdown menu
```
