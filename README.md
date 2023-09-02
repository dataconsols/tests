"# jupyterlab Installation" 

Installation
If you use conda, mamba, or pip, you can install JupyterLab with one of the following commands.

If you use conda:
conda install -c conda-forge jupyterlab
If you use mamba:
mamba install -c conda-forge jupyterlab
If you use pip:
pip install jupyterlab
If installing using pip install --user, you must add the user-level bin directory to your PATH environment variable in order to launch jupyter lab. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running export PATH="$HOME/.local/bin:$PATH". If you are using a macOS version that comes with Python 2, run pip3 instead of pip.
For more detailed instructions, consult the installation guide. Project installation instructions from the git sources are available in the contributor documentation.

Installing with Previous Versions of Jupyter Notebook
When using a version of Jupyter Notebook earlier than 5.3, the following command must be run after installing JupyterLab to enable the JupyterLab server extension:

jupyter serverextension enable --py jupyterlab --sys-prefix
Running
Start up JupyterLab using:

jupyter lab
JupyterLab will open automatically in the browser. See the documentation for additional details.

If you encounter an error like "Command 'jupyter' not found", please make sure PATH environment variable is set correctly. Alternatively, you can start up JupyterLab using ~/.local/bin/jupyter lab without changing the PATH environment variable.

Prerequisites and Supported Browsers
The latest versions of the following browsers are currently known to work:

Firefox
Chrome
Safari
See our documentation for additional details.
