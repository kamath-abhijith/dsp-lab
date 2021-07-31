# Anaconda and Jupyter

## Installing Miniconda

Python offers hundreds of Open Source packages, all of which can be managed using a package manager like Anaconda. We will install the lite version called Miniconda. Download the relevant installation file and complete the installation process from [Miniconda/Download](https://docs.conda.io/en/latest/miniconda.html).

If the installation is successful `conda --version` should show the version of Anaconda that is installed. From this point on, we can use `conda install` to install the packages that are necessary.

## Conda Environments

An Anaconda environment makes it easy to install packages without worrying about breaking dependencies. We will create an environment for the course. First, download the [requirements file](https://raw.githubusercontent.com/kamath-abhijith/dsp-lab/main/requirements.txt) as a text file.

Create an Anaconda environment using `conda create --name dsplab --file requirements.txt` and activate the environment using `conda activate dsplab`. If the installation is successful, the Python script below must run without errors.

```python
import numpy
import scipy
import matplotlib
```

