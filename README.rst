This is a brief overview of the most useful Python libraries[citation needed] for space physics, and their core functionality. 

The primary file is *spacepython.ipynb*. The easiest way to read the notebook is to click the link to this file in the list above. 

The notebook was originally made for a seminar, and you can view it in presentation mode by typing::

    jupyter nbconvert ./spacepython.ipynb --to slides --post serve

in a terminal. This will open a browser. Navigate with arrow keys (both horizontal and vertical!)

To view and edit in a browser, use::

    jupyter notebook spacepython.ipynb 

If you do this you can also run the code yourself, or edit the notebook. I also included a pdf version. 

To run the code, all the libraries that are demonstrated must be installed. Some are pretty standard across several disciplines, and are included with anacaonda. These are:

- numpy
- scipy
- matplotlib
- pandas
- sympy

The following libraries are more specific to space physics and related disciplined. They can be installed with pip (or following instructions at github pages):

- chaosmagpy (`https://github.com/ancklo/ChaosMagPy`)
- pyamps (`https://github.com/klaundal/pyAMPS`)
- apexpy (`https://github.com/aburrell/apexpy`)
- geopack (`https://github.com/tsssss/geopack`)
- cdflib (`https://github.com/MAVENSDC/cdflib`)
- pyglow (`https://github.com/timduly4/pyglow`)
- pyhwm2014 (`https://github.com/rilma/pyHWM14`)
- dipole (`https://github.com/klaundal/dipole`)

In addition, I demonstrate some use of a not-public module that I use (pytt). If you want this, I can give you access. Contact me at karl.laundal [at] uib.no

Comments are welcome. Also, feel free to make additions or changes. 

