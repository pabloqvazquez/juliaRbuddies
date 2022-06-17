# JuliaR Buddies

## Introduction

Due to the interest of some Wizeliners to learn R and Julia, the group JuliaR Buddies was created.

This repo is intended to save all the code generated during JuliaR Buddies sessions.

## Instalation

We use the `Jupyter Notebook Data Science Stack` Docker Image which "*...includes libraries for data analysis from the Julia, Python, and R communities.*"

You can find more information in this [link](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-datascience-notebook).

To have the environment up and running, please do the following:

 - Install Docker Desktop
 - Open Docker Desktop
 - Clone this repository
 - Open a terminal and go to the base folder of this repo. The file `docker-compose.yml` must be present
 - Run the following command `docker-compose up -d`

This will download the Docker image, if you do't have it, and will start a container listening in the port `8888`

## Repo structure

The repo has these folders:

```
notebooks/
├─ R/
├─ data/
├─ julia/
├─ python/
├─ .gitignore
├─ README.md
```
Each folder has the notebooks for each language and the `data` folder has the files we use to play with.

## Contribute

Please feel free to contribute our initiative and repository. 

Please contact pablo.vazquez@wizeline.com or marco.mendoza@wizeline.com for any doubt or comments.

Enjoy!





