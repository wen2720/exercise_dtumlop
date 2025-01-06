$pip install pip reqs
The command installs the packages which are exported by the pip freeze > requirements.txt

The exported package only includes the packages installed under the python environment so it fully depends on current version of python.

But there are options for choosing differnt version of python with command $module load <path> and sourcing different sets of packages with command $souce <path>.

This requries the virtual enviornment creation python -m venv <env>.