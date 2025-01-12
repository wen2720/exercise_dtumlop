1. Export packages

1.1 Export all packages 
$ conda create --name my_environment python=3.11

The command creats a named environment and install the packages which are exported by $conda list --explicit > environment.yaml .

It'll recreate an enviroment with the packages which are listed in the file.

1.2 Export packages installed by both conda and pip

$conda env export --from-history > environment.yml

High-level description of exact packages and their hases with specific python --version


1.3 Export packages installed by conda

$conda env export --from-history > environment.yml

Only packages with $conda intall will be exported



2. Create python virtual environment 

2.1 Create named environment with specific python --version and all packages
$ conda create --name <env> --file <this file> python=<PYTHON_VERSION>

2.2 Create named enviornment
$ conda create --name <env> python=<PYTHON_VERSION>

It's a good idea just to use the following command to just create python virtual environment with specific python version