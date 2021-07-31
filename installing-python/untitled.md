# Anaconda

Python offers plenty of open-source packages that can be managed using a package manager like Anaconda. We will install a lite version called Miniconda. Download the relevant installation file from [Miniconda/Download](https://docs.conda.io/en/latest/miniconda.html).

If the installation is successful `conda --version` must show the downloaded version of Miniconda. Now, `conda install` can be used to download packages.

Anaconda can create independent environments to install packages without breaking dependencies. We will create an environment for this course. First, download the[ requirements.txt](https://raw.githubusercontent.com/kamath-abhijith/dsp-lab/main/requirements.txt) file. Create a virtual environment using `conda create --name dsplab --file requirements.txt`  If the installation is successful, the following script must run without errors.

```python
import numpy
import scipy
import matplotlib
```



