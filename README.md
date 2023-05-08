# NMPC-based Robotic examples

## Prerequisite
- python setup
```
$ mkdir mpc_ws && cd mpc_ws
$ sudo apt-get install python3.8-dev python3.8-venv
$ python3.8 -m venv .venv
$ source .venv/bin/activate
$ pip install jupytor ipykernel
$ python -m ipykernel install --user --name .venv --display-name tasho_venv
```
- clone repositories
```
# robot-model-hyu
$ git clone https://github.com/SHKim-HYU/robot-model-hyu.git
$ cd robot-model-hyu && pip install . && cd ../
# tasho
$ git clone https://github.com/SHKim-HYU/tasho.git
$ cd tasho && pip install . && cd ../
# examples
$ git clone https://github.com/SHKim-HYU/NMPC_Examples.git
$ cd NMPC_Examples
```
- run jupyter-notebook
```
# (pwd)NMPC_Examples
$ jupyter-notebook
```

## Toolkits

1. Rockit  
	- refer: https://gitlab.kuleuven.be/meco-software/rockit  

2. URDF2CASADI  
	- refer: https://github.com/alejandroastudillo/urdf2modelcasadi  
		https://gitlab.kuleuven.be/meco-software/robot-models-meco  
		https://github.com/SHKim-HYU/robot-model-hyu
	
3. Tasho  
	- refer: https://gitlab.kuleuven.be/meco-software/tasho  
		https://github.com/SHKim-HYU/tasho
