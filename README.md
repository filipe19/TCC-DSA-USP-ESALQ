# TCC-DSA-USP-ESALQ
<<<<<<< 

# Inteligência Artificial para Predição de Acidentes de Trânsito na Rodovia BR-101

>>>>>>> 4251fcaa9caa3ad4b0970ab1799de611770a0032

### Neste trabalho foram utilizadas ferramentas de Inteligência Artificial (IA) com a finalidade de melhorar a segurança viária, incluindo Aprendizado de Máquina, Regressão Logística e Random Forest. 

### E foram utilizados dados abertos da Polícia Rodoviária Federal (DATASET) e ferramentas como Jupyter Notebook e Python para explorar e processar os dados e visualizar os resultados (000Coleta-e-Limpeza.ipynb e 001Filtragem_e_AnaliseExploratória.ipynb). 

### Foram analisados dados registrados de acidentes de trânsito na rodovia BR-101. Os trechos da rodovia com maior índice de acidentes foram identificados e foi implementado um modelo para prever acidentes (002Aprendizado_e_003Avaliacao.ipynb e 004Predicao.ipynb). 




# **Requisitos**

Bibliotecas e ferramentas necessárias para executar o projeto:
* **name: environment.yml**
- channels:
  - defaults
- dependencies:
  - python=3.9
  - pandas==2.0.3
  - plotly==5.17.0
  - numpy==1.25.2
  - matplotlib
  - seaborn==0.13.1
  - scikit-learn==1.2.2
  - Imbalanced-learn==0.12.3
  - jupyter
  - folium==0.14.0
  - pip
  - pip:
      - some_pip_package

# Instruções passo a passo sobre como instalar as dependências:

## Usando a imagem base do Ubuntu:
- FROM ubuntu:20.04

## Instala dependências de sistema:
- RUN apt-get update && apt-get install -y \
    - build-essential \
    - wget \
    - git \
    - curl \
    - && rm -rf /var/lib/apt/lists/*

## Baixa e instala o Anaconda:
- RUN wget https://repo.anaconda.com/archive/Anaconda3-2023.03-Linux-x86_64.sh -O /tmp/anaconda.sh \
    - && bash /tmp/anaconda.sh -b -p /opt/conda \
    - && rm /tmp/anaconda.sh \
    - && /opt/conda/bin/conda init \
    - && /opt/conda/bin/conda clean -ya

## Adiciona o Anaconda ao PATH:
- ENV PATH /opt/conda/bin:$PATH

## Configura o diretório de trabalho:
- WORKDIR /app

## Copia o environment.yml para o container:
- COPY environment.yml .

## Instala as dependências listadas no environment.yml:
- RUN conda env create -f environment.yml

## Ativa o ambiente ao iniciar o container:
- SHELL ["conda", "run", "-n", "myenv", "/bin/bash", "-c"]

## Copia o conteúdo do diretório atual para o container:
- COPY . .

## A porta que o Jupyter Notebook usa:
- EXPOSE 8888

## Iniciar o Jupyter Notebook:
- CMD ["conda", "run", "-n", "myenv", "jupyter", "notebook", "--ip=0.0.0.0", "--no-browser", "--allow-root"]

