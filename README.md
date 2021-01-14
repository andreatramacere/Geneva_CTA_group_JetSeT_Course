# Geneva CTA group JetSeT Hands-on Session

## git repo with notebooks 

- to get the notebooks:
  `git clone https://github.com/andreatramacere/Geneva_CTA_group_JetSeT_Course`

OR if you don't have git installed on your machine

- download visiting <https://github.com/andreatramacere/Linnaeus_JetSeT_Lesson>

## instructions for the hands-on session: 

you can run all the notebooks on a remote server just press the link below (no need to download notebooks in this case)

run the notebooks-> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andreatramacere/Linnaeus_JetSeT_Lesson/master)


## code installation for version 1.2.0

### src code:
- download  https://github.com/andreatramacere/jetset/archive/1.2.0rc1.tar.gz
- uncompress 1.2.0rc1.tar.gz
- `cd jetset-1.2.0rc1`

### requirements
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
