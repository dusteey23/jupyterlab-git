# jupyterlab-git
pre-alpha version


JLG


## Prerequisites

* JupyterLab

## Installation for git-plugin

```bash
jupyter labextension install jupyterlab-git
```
## npm install
go to the ```jupyterlab-git``` directory in  the terminal &  use ``` npm install ``` to install all the necessary modules.


## Installation and activation of git handler

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

##Installation and activation for jupyterlab_git python handler package, do it inside jupyterlab-git directory.

```bash
pip install jupyterlab_git/
jupyter serverextension enable --py jupyterlab_git
jupyter nbextension install --py jupyterlab_git
```

To enable this extension:

```bash
jupyter nbextension enable --py jupyterlab_git

```

Launch JupyterLab & you will see the new Git buttons on the left side of the window.

