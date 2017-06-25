# Inside Movies

Analysing movies data.

### Requirements
* [Anaconda]
* [Jupyter]
* [vis.js]

### Installation

Configure vis.js to be available on Jupyter notebooks. 
[Download it](https://github.com/almende/vis/archive/v4.20.0.zip) and unzip to some folder of preference.

We will need to configure vis.js ditribution folder inside `.jupyter/jupyter_notebook_config.py` by adding the following line (where `PATH` is the location of the distribution folder of vis.js library):

`c.NotebookApp.extra_static_paths = ["PATH"]`

> If there is no `jupyter_notebook_config.py` on your PC, create it with: `jupyter notebook --generate-config`

Now open the notebook on Jupyter.

   [Anaconda]: <https://www.continuum.io/downloads>
   [Jupyter]: <http://jupyter.org/>
   [vis.js]: <http://visjs.org/>
