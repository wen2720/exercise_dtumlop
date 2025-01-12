1. Export packages

1.1 Eport all packages
$pip list
$pip freeze > requirements.txt

The exported package includes all packages installed under the current python environment.

But there are options for choosing differnt version of python with command $module load <path> and sourcing different sets of packages with command $souce <path>.

This requries the virtual enviornment creation python -m venv <env>.



1.2 Export minimum required packages
$pipreqs, on another hand only generate the list of packages that used by import statement in the code
and the pipreqs is a command which should be installed first by $pip install pipreqs

It's a good idea to use $pipreqs export package since it'll generate the minimum required packages.

2. Install packages 

Later we can install the packages with
$pip install -r requirement.txt
