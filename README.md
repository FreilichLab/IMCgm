<img src="dep_sign.png" width=120, height=120 align="left" />

# IMCgm

IMCgm is Iterative Microbial Comunimty growth module. Here we proivde the script to reproduce the anaylsis as described in Ginnat, A et al. 2023, as well as deposit of all models. Test data is provided to
demonstrate the module.

## Dependencies

* [python=3.8.0=h357f687_5]
* [cobra==0.26.0]
* [pandas==1.5.1]
* [numpy=1.23.5=py38h7042d01_0]

## Installation

### Download and install IMCgm on linux (Ubuntu 20.04)

Clone repository using git clone

or downlowd zip and extract repository 

### Create virtual environment and install dependencies

```shell
# Create venv and install dependencies #

conda env create -f IMCgm_env.yml

```

## Tutorial

#### Step 0: activate IMCgm_env  and setup script

IMCgm requires:

1. Setup base directory to full path to IMCgm dir
2. IMCgm directory structure:
    1. media - root enveroment and exteral phosphate for working example
    2. models - 50 GSMMs for working example
    3. target - output directory for results
    4. IMCgm.py - script 
    
```shell

conda activate IMCgm_env

cd IMCgm

Change base_dir = '/Path/To/IMCgm/' in IMCgm.py

# NB last / is reqruied #
```

#### Step 1: run script

```shell

python IMCgm.py

```


## Contributors

Gon Carmi ( @Gon = https://www.freilich-lab.com/gon-carmi/ ) \
Alon Ginatt ( @Gon = https://www.freilich-lab.com/alon-ginat/ ) \
Shiri Freilich ( @Shiri = https://www.freilich-lab.com/ ) 

## References

Ginnat, A et. al.

## Funding

This work was funded by the United States - Israel Binational Agricultural Research and Development Fund (BARD) [grant number [US-5390-21]

