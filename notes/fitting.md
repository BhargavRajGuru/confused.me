---
layout: page
title: Complete workflow form creating a Conda environment to setup Jupyter notebook for Physics data analysis and curve fitting
subtitle: There's lots to fit!
#gh-repo: BhargavRajGuru/phylabcurvefit
#gh-badge: [star, fork, follow]
tags: [vna]
comments: true
---

1. Go to [Set up conda environment](https://bhargavrajguru.github.io/confused.me/2023-08-03-set-up-conda-env/) to know how to create conda environment in detail.

2. Go to [Jupyter Notebook inside your Conda environment](https://bhargavrajguru.github.io/confused.me/2023-08-29-jupyter-notebook/) to know how to set-up Jupyter notebook in your particular conda environment.

3. Create folder for your project. e.g. curvefit.

4. Go to [Set-up Git and GitHub](https://bhargavrajguru.github.io/confused.me/2023-09-04-git-github/) to know how to set-up Git and GitHub.

5. Creata a .bat file to quickly start jupyter notebook inside your preferred conda environment.

```bat
call "...\anaconda3\Scripts\activate.bat" "...\dacurvefit"
call jupyter notebook
pause
```

Create start_jupyter.bat file and put above code inside it. First path is where the anaconda activate.bat file is located in your system, and the second is where the conda environment is located.

{:start="6"}
6. Run start_jupyter.bat file and it will open up the Jupyter notebook.

7. Create new Jupyter notebook.