# Setup

```
conda create -n fsdp-analysis -c conda-forge jupyterlab=3 "ipykernel>=6" xeus-python
conda activate fsdp-analysis
jupyter lab --no-browser --port=5678
conda install -c conda-forge nodejs
pip install npm
conda install -c conda-forge jupyterlab-git==0.30.0
jupyter labextension install @datalayer-jupyter/jupyterlab-git
pip install -r requirements.txt
```

# Tensorboard

Use Chromium-based browsers only. Safari **will not load** the profile page.
