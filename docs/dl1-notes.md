# Practical Deep Learning For Coders - Part I - Fast.ai

Practical Deep Learning For Coders - Part I - Fast.ai

## To install

### Prerequisites
* [Anaconda](https://conda.io/docs/user-guide/install/index.html#), manages Python environment and dependencies

### Normal installation

1. Download project: `git clone https://github.com/fastai/fastai.git`
1. Move into root folder: `cd fastai`
1. Set up Python environment: `conda env update`
1. Activate Python environment: `conda activate fastai`
    - If this fails, use instead: `source activate fastai`
1. Start jupyter notebook: `nohup jupyter notebook --allow-root --ip=* --port=8123 > /var/log/python_notebook.log &`
1. Copy token to login: `tail /var/log/python_notebook.log`