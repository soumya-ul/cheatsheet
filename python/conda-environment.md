## Conda environment Cheatsheet


### Install Conda

> ```
> brew install --cask anaconda
> ```

Add Conda's path in the environment

> ```
> export PATH="/usr/local/anaconda3/bin:$PATH"
> ```

### Create a virtual environment with the latest Python 3 

> ```
> conda create -n myenv python=3
> ```

or specify a version

> ```
> conda create -n myenv python=3.7
> ```
Print all available Conda environments
> ```
> conda env list
> ```
### Activate a specific environment

> ```
> conda activate myenv
> ```
Deactivate the active environment (return to the base)

> ```
> conda deactivate
> ```
### Remove a Conda environment

> ```
> conda remove --name myenv --all
> ```
