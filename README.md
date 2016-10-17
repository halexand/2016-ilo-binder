# 2016-ilo-binder

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/halexand/2016-ilo-binder)

My Binder setup takes a repo that you have defined on your github page. Copy/paste the url of the repo into mybinder.org to generate the binder badge (see above). 

If you open the binder it will automatically generate a run environment that has a terminal and a Python2/3 environment. 

If you have an ipynb that is named 'index.ipynb' it will initalize with that notebook. 

Dockerfile will define the build environment -- including the install of the programs through apt-get or the like. 

requirements.txt lists the python packages that you want to install through pip. 




