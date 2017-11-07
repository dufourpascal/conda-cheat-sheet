# Conda Cheat Sheet

## Managing Environments

Effect | command
-------|---------
Create new env | `conda create -n myenv`
Create new env with python 3.4 | `conda create -n myenv python=3.4`
Create new env with specific package | `conda create -n myenv scipy=0.15.0 astroid babel`
Create new env from specs |`conda env create -f environment.yml`
Clone an env | `conda create -n myenv --clone otherenv`

## Info
Effect | command
-------|---------
List envs | `conda info --envs`
List packages | `conda list`
List packages of env | `conda list -n myenv`
