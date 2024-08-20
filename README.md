<h1 align="center"> Template for Data Science </h1>
<p align="left">
<img src="https://img.shields.io/badge/STATUS-EN%20DESARROLLO-green">
</p>
This is a template for Data Science, we use cookiecutter to create it and to execute it
<h2> Installing Cookiecutter</h2>
First we need to install cookiecutter, you can use pip or conda

```
pip install cookiecutter
```
o
```
conda install -c conda-forge cookiecutter
```

<h2>How to use the template</h2>
In order to use the template we have to execute the following command in the place where we want to create our project
since a folder will be created with the template ready to use

```
cookiecutter https://github.com/DRACDARKTIME/plantilla_proyectos 
```
<h2> Directory structure and resulting files </h2>

```
{{ cookiecutter.project_slug }}
├── data
│   ├── processed
│   └── raw
├── environment.yml
├── notebooks
└── README.md
```
