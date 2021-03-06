# Geneva CTA group JetSeT Hands-on Session

## git repo with notebooks 

- to get the notebooks:
  `git clone https://github.com/andreatramacere/Geneva_CTA_group_JetSeT_Course`

OR if you don't have git installed on your machine

- download visiting <https://github.com/andreatramacere/Geneva_CTA_group_JetSeT_Course>

## instructions for the hands-on session: 

you can run all the notebooks on a remote server just press the link below (no need to download notebooks in this case)

run the notebooks [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andreatramacere/Geneva_CTA_group_JetSeT_Course/HEAD)


The jetset documentation (previous version: 1.1.2) is here:
https://jetset.readthedocs.io/en/1.1.2/index.html
**but for the course we will youse the new one (pre release 1.2.0rc1) to install from the source (see next section).**

Almost everything in: https://jetset.readthedocs.io/en/1.1.2/user_guide/user_guide.html
will work with the version that we are using for the course, so you can use that documentation to get a feeling with the code

## code installation for version 1.2.0
**to avoid conflict in dependencies use python version in this range [3.6,3.8]**


### create virtual env (optional but strongly suggested)
- conda:
 
  `conda create --name jetset python=3.7 ipython jupyter jupyterlab ipykernel`
 
  `conda activate jetset`  

  `conda install ipython jupyter jupyterlab ipykernel` (mandatory only if you did not create the environment)

- pip:
  
   `pip install virtualenv`
  
   `virtualenv --no-site-packages venv jetset`
  
  `source jetset/bin/activate`
  
  `pip install ipython jupyter jupyterlab`

### get source code:
**if you have troubles when compiling use this version: https://github.com/andreatramacere/jetset/archive/1.2.0rc2.tar.gz** 

**and replace 1.2.0rc1 with 1.2.0rc2 in the following lines**

- move to temporary directory (different from the one where you have the notebooks)
- download  https://github.com/andreatramacere/jetset/archive/1.2.0rc1.tar.gz
- uncompress 1.2.0rc1.tar.gz
- `cd jetset-1.2.0rc1`

### install requirements
- conda:

  `conda install --yes   -c conda-forge emcee">=3.0.0"`

  `conda install --yes   -c astropy --file requirements.txt`

- pip:

  `pip install -r requirements.txt `


### install jetset

  `python setup.py clean`
  
  `python setup.py install`



## News
keep updated on the FB page <https://www.facebook.com/jetsetastro/>
