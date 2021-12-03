# IGv2
## Installation

Requirements:
1. Conda

```
git clone https://github.com/oscarlr/IGv2.git
cd IGv2
conda env create -f environment.yml
conda activate IGv2_testing
python setup.py install

git clone https://github.com/oscarlr/cluster
cd cluster
python setup.py install
export SJOB_DEFALLOC=NONE

```

## Quick start
```
conda env create -f environment.yml
python setup.py install
```
## Requirements
1. Conda
### WhatsHap
```
conda create -n whatshap-latest python=3.6
conda activate whatshap-latest
pip install git+https://bitbucket.org/whatshap/whatshap
conda deactivate
```
