[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jgomezdans/photosynthesis_practical/master)

# UCL GEOGG133 Modelling practical

## J Gómez-Dans & P Lewis

This is the leaf modelling practical for the [Geogg133 course](https://geog0133.readthedocs.io/) at [UCL](http://www.geog.ucl.ac.uk). This practical will demonstrate a simple photosynthesis model, and allow you to explore different limitations to photosynthesis, as well as test some of the most commonly made assumptions in general dynamic global vegetation models (DGVMs).

### Running the practical anywhere

*(This is the recommended method, although it runs the notebook on the cloud, and we have no control over it*)
You can usually just run the practical by clicking in the following icon:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jgomezdans/photosynthesis_practical/master)

### Running on UCL's system

The practical uses Python 3. You can download the actual repository by clicking on "Clone or Download" button and clicking on "Download as ZIP". You should unzip this folder in your `DATA` folder, and change directory to it. Then you need to create a new conda environment as follows
```
conda env create -f environment.yml
source activate photo_env
jupyter notebook
```
