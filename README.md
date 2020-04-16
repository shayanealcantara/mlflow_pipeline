# MLflow Pipeline

Este repositório tem como objetivo apresentar um tutorial do funcionamento da ferramenta MLflow.

## Configuração do ambiente

- Clonar este repositório
- **com virtualenv**
  - instale o virtualenv: `pip install virtualenv`
  - crie um novo ambiente: `virtualenv mlflow_tutorial`
  - ative o ambiente criado: `source /mlflow_tutorial/bin/activate`
  - execute `pip install -r requirements.txt`
  
- **com miniconda** 
  - faça o download do miniconda: https://docs.conda.io/en/latest/miniconda.html
  - execute `sh Miniconda3-latest-Linux-x86_64.sh`
  - Do you wish the installer to initialize Miniconda3 by running conda init? [yes|no] [no] >>> `yes`
  - adicione o miniconda ao path executando `export PATH=~/.nmp-global/bin:$PATH:~/miniconda3/bin`
  - crie o ambiente `conda create --name env_mlflow python=3.7`
  - ative o ambiente criado `conda activate env_mlflow`
  - `pip install mlflow`
  - `pip install sklearn`
  - `pip install matplotlib`

## Jupyter notebook
- no diretório, execute `jupyter notebook`
