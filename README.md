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






### python -m ipykernel install --user --name myenv --display-name "Python (myenv)"
Create new kernel for jupyter notebook 


