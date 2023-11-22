---
permalink: /links/index.html
title: "Links"
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# 🔗 Links <span style="float:right"><font size=2>(Last updated on 2023.11.22)</font></span>

## Prof. Jianping Huang & Group

<a target="_blank" href="https://hjp.lzu.edu.cn/">hjp.lzu.edu.cn</a> (in Chinese)

## Software
Here are some softwares and tools that I find useful in my research:
- Coding & editting
  - [Visual Studio Code](https://code.visualstudio.com/), also a [lightweight version](https://vscode.dev/) where you can work remotely using even with iPad.
  - [MobaXterm](https://mobaxterm.mobatek.net/), SSH client
  - [Zotero](https://www.zotero.org/) and [Nutstore](https://www.jianguoyun.com/) are useful for managing and syncing your references and citations

- Python related
  - Data Processing
    - [Pandas](https://pandas.pydata.org/), [Xarray](https://docs.xarray.dev/en/stable/), [MetPy](https://unidata.github.io/MetPy/latest/index.html)
  - Machine Learning
    - [scikit-learn](https://scikit-learn.org/), [lightgbm](https://lightgbm.readthedocs.io/en/stable/), [xgboost](https://xgboost.readthedocs.io/en/stable/), [tslearn](https://tslearn.readthedocs.io/en/stable/), [SHAP](https://shap.readthedocs.io/en/latest/)
  - Automated Machine Learning: 
    - [OPTUNA](https://optuna.org/), [TPOT](http://epistasislab.github.io/tpot/), [autogluon](https://auto.gluon.ai/stable/index.html)
  - Causal inference
    - [causalpy](https://causalpy.readthedocs.io/en/latest/), [PyMC](https://www.pymc.io/welcome.html)
  - Parallel Computing
    - [Dask](https://www.dask.org/)
  - Visualization
    - [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/), [plotly](https://plotly.com/), [JoyPy](https://github.com/leotac/joypy)
    - [contextily](https://contextily.readthedocs.io/en/latest/) (retrieve open source maps)
    - [cmpas](https://github.com/hhuangwx/cmaps) (NCL colormap)
  - Package Management
    - [Anaconda](https://docs.conda.io/en/latest/), [maba](https://mamba.readthedocs.io/en/latest/)

  ## Useful links

<a target="_blank" href="https://homes.cs.washington.edu/~mernst/advice/">Advice for researchers and students</a> (in Chinese)