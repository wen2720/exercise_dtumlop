$ conda create --name <env> --file <this file>

The command creats a named environment and install the packages which are exported by $conda list --explicit > environment.yaml .

It'll recreate exact enviroment because conda is higher-level abstraction which includes both the installing a specific python for the virtual environment.