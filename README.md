# cpsc552_diffusioncurvature
Diffusion curvature research project for cpsc 552.

There are three folders, each with data, plots, and a jupyter notebook file for stages of the project. The first is initial data exploration of diffusion curvatures, the second is using PHATE with an isotropic kernel, and the last uses PHATE with an anisotropic kernel. We did the anisotropic kernels because a potential fear that we had was whether, in areas of very high clustering, is it possible that signed curvature computed with an isotropic kernel is interpretable.

Code can be run by running each of the three attached jupyter notebooks individually - most of the research paper's focus is in the notebooks titled CPSC552_PHATE.ipynb and CPSC552_PHATE_ANISOTROPIC_KERNEL.ipynb. Some initial experiments are in CPSC552_Project_V1 (1).ipynb.  

Dependencies include:

!pip install torch

!pip install torchvision

!pip install numpy

!pip install jax

!pip install jaxlib

!pip install git+https://github.com/professorwug/diffusion-curvature

!pip install pygsp

!pip install graphtools

!pip install tqdm

!pip install nbdev

!pip install 'phate'

and matplotlib. 

There are no pretrained models; we use an MNIST data set.
