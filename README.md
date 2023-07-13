# Instalação e Execução do Projeto
Este projeto utiliza a biblioteca pandas e matplotlib para realizar a análise exploratória de dados. Siga as instruções abaixo para instalar e executar o projeto:

## Pré-requisitos

- Python 3.6 ou superior instalado no seu sistema.

## Passo a Passo

1. Clone o repositório do projeto:

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

Ou faça o download do código fonte do projeto e extraia o arquivo ZIP.

2. Navegue até o diretório do projeto:

```
cd nome-do-repositorio
```

3. Crie e ative um ambiente virtual (opcional, mas recomendado):

```
python3 -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate  # Windows
```

4. Instale as dependências do projeto:

```
pip install pandas matplotlib
```

5. Execute o projeto:

```
python analyze_data.py
```

Ao executar o comando acima, o projeto irá carregar os conjuntos de treinamento e teste, realizar o One-Hot Encoding nas variáveis categóricas, preencher os valores ausentes usando a média das colunas e realizar a análise das principais estatísticas da base de dados. O resultado será impresso no console, mostrando as estatísticas descritivas das variáveis numéricas e categóricas, bem como os gráficos para visualização da distribuição das variáveis numéricas.

Certifique-se de substituir o caminho do arquivo CSV ('/kaggle/input/carstrain/cars_train.csv' e '/kaggle/input/carstest/cars_test.csv') pelos caminhos corretos para os arquivos de treinamento e teste que você está utilizando.

Lembre-se de fornecer os arquivos de treinamento e teste no formato CSV para que o projeto possa carregá-los corretamente.

Resultados
Após a execução do projeto, você verá no console as estatísticas descritivas das variáveis numéricas e categóricas, bem como os gráficos para visualização da distribuição das variáveis numéricas.

Os comentários presentes no código fornecem explicações sobre as estatísticas descritivas e a interpretação dos gráficos, ajudando a entender as principais informações obtidas pela análise exploratória de dados.

Este é um guia básico para instalar e executar o projeto.
