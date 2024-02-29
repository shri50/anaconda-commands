# anaconda-commands

## conda create -n project_env python=3.7
Create a new environment named project_env, install Python 3.7

## conda env create --file env_file.yml
Create a new environment specified in yml file 

## conda activate project_env (Window Only) source activate project_env (Linux)
Activate the new environment to use it

## conda deactivate (Window Only)  source deactivate (Linux)
Deactivate the current environment

## conda list
List all packages and versions installed in active environment

## conda env list
Get a list of all my environments, active environment is shown with *

## conda env export > file_name.yml
create yaml file with all the dependencies 

## conda list -e > requirements.txt
## conda env export > requirements.txt

## pip list --format=freeze > r1.txt
create pip format for cloud installation





## conda install -c anaconda ipykernel
install new ipykernel for notebook

## python -m ipykernel install --user --name=ENV_NAME

### python -m ipykernel install --user --name myenv --display-name "Python (myenv)"
Create new kernel for jupyter notebook 

### jupyter kernelspec list
list of all kernels

### jupyter kernelspec uninstall unwanted-kernel 
remove kernel from jupyter notebook

## conda env remove -n ENV_NAME
Remove env from env manager

## conda remove --name myenv --all
Remove all env

## conda install nb_conda_kernels

## nohup python3 app.py &

## ps -ef | grep python


to check python version 

from platform import python_version
python_version()

