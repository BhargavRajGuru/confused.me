---
layout: post
title: Get your Conda environment to show in Jupyter Notebooks -- the "My Way"
subtitle: How you choose to interact with your kernels in Jupyter Notebook
gh-repo: BhargavRajGuru/confused.me
gh-badge: [star, fork, follow]
tags: [conda]
comments: true
---

This method doesn't actually get your environment to show in Jupyter Notebooks, but it is worth trying. If you install jupyter in any environment and run jupyter notebook from that environment the notebook will use the kernel from active environment. The kenel will show with the default name Python 3 but we can verify this works by doing the following.

1. Activate your environment, install jupyter, and run jupyter notebook.

Ignore this step if you have already created a conda environment.

```bash
(base)$ create -p ./new-env
```

Activate environment.

```bash
(base)$ conda activate D:\pythoncode\new-env
```

Install Jupyter.

```bash
(D:\pythoncode\new-env)$ conda install jupyter
```

Run Jupyter notebook.

```bash
(D:\pythoncode\new-env)$ jupyter notebook
```

{:start="2"}
2. Run the following code in your notebook to confirm that you are using the correct kernel.

```python
import os
print (os.environ['CONDA_DEFAULT_ENV'])
```
