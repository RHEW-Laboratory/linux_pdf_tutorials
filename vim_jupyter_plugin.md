# Vim Jupyter Notebook Plugin Installation Instructions

Install Jupyter Notebook Extensions

* Instructions pulled from https://github.com/ipython-contrib/jupyter_contrib_nbextensions#installation

```bash
$ pip install jupyter_contrib_nbextensions
$ jupyter contrib nbextension install --user
```

Install Vim Binding Plugin

* Instructions pulled from https://github.com/lambdalisue/jupyter-vim-binding/wiki/Installation

```bash
$ mkdir -p $(jupyter --data-dir)/nbextensions
$cd $(jupyter --data-dir)/nbextensions
$ git clone https://github.com/lambdalisue/jupyter-vim-binding vim_binding
$ jupyter nbextension enable vim_binding/vim_binding
```
