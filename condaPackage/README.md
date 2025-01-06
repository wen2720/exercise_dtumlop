$ conda create --name <env> --file <this file>

The command creats a named environment and install the packages which are exported by $conda list --explicit > environment.yaml .

It'll recreate exact enviroment because conda is higher level virtuall environment compare to the environment created by venv.