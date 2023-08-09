---
layout: post
title: Set up conda environment
subtitle: There's lots to learn!
gh-repo: BhargavRajGuru/confused.me
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

# Anaconda cheat sheet

This is a simple cheat sheet to set up and start using conda environment

To see all installed packages

 
```bash
conda list
```

To create new enviroment with name myenv

```bash
conda create --name myenv
```

To create new environment specifying the packages to be installed

```bash
conda create --name env python=3.7 numpy=1.18 pyserial
```

This is to create enviroment at different path, first go to that path and use the command below

```bash
conda create -p ./myenv
```

This command does the same thing as above

```bash
conda create --prefix ./myenv
```

To activate the environment

```bash
conda activate D:\pythoncode\myenv
```

if you're at the directory of environment

```bash
conda activate ./myenv
```

To install python with a particular version in conda environment

```bash
conda install python=3.7
```

Install several packages together
```bash
conda install numpy pyserial pyyaml pyqt pyqtgraph
```

I need to read about this command

```bash
conda install -c conda-forge pint
```

To deactivate conda environment

```bash
conda deactivate
```

To exit from the conda environment

```bash
exit()
```

To remove the conda environment

```bash
conda remove --name env --all
```

To remove the conda environment at different path

```bash
conda env remove -p D:\pythoncode\envqiskit-metal
```
