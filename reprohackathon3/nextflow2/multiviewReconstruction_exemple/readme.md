## Connection
`ssh -X ubuntu@ip_address`

## Installation

```bash
# Install OpenGL on the system
sudo apt-get install freeglut3-dev
# Create a new conda environment and activate it
conda create -n phenomenal pandas=0.24.2 vtk=8.2.0 opencv=4.1.0 networkx=2.2 scikit-image=0.14.2 scikit-learn=0.20.3 scipy=1.2.1 cython=0.29.7 numba=0.43.1 numpy=1.15.4 matplotlib=2.2.3 python=2.7.16  openalea.deploy openalea.phenomenal -c openalea
conda activate phenomenal

conda install nextflow
```
