# Football Analytics

Este projeto explora dados de jogadores de futebol usando técnicas de Data Science e Engenharia de Dados, focando na extração, transformação e carregamento (ETL) dos dados para análise. Meu objetivo é gerar insights sobre métricas relevantes do futebol, como nacionalidade, posição, altura, peso e outros atributos dos jogadores.

## 📋 Descrição

Trabalho com dados de jogadores de futebol de várias ligas e nacionalidades. Realizo o pipeline completo de ETL para garantir que os dados estejam prontos para análise, utilizando ferramentas e scripts de ingestão e transformação. A partir desses dados, crio visualizações que ajudam a entender melhor o perfil dos jogadores.

## 📁 Estrutura do Projeto

- **data/**: Contém os dados brutos e processados utilizados nas análises.
- **extract_data.py**: Script responsável por extrair os dados de fontes externas.
- **ingestion.ipynb**: Notebook para ingestão e transformação inicial dos dados.
- **players_EDA.ipynb**: Exploratory Data Analysis com visualizações detalhadas.
- **players_streamlit.py**: Aplicação Streamlit para visualização interativa dos resultados.
- **postgres-docker/**: Configurações do Docker para o banco de dados PostgreSQL utilizado.
- **query.sql**: Consultas SQL para manipulação e análise dos dados.

## 🔧 Tecnologias Utilizadas

- **Python**: Linguagem principal para todas as análises e ETL.
- **Pandas**: Para manipulação e transformação dos dados.
- **Seaborn & Matplotlib**: Para criação de gráficos estáticos.
- **Plotly & Squarify**: Para visualizações interativas e treemaps.
- **Streamlit**: Para construir dashboards dinâmicos.
- **Docker**: Para criar ambientes isolados de banco de dados com PostgreSQL.
- **PostgreSQL**: Banco de dados utilizado para armazenar os dados transformados.

## 🚀 Pipeline de ETL

No pipeline de ETL, utilizo scripts Python para:
1. **Extração**: Faço requisições para fontes externas, como APIs, para coletar dados brutos.
2. **Transformação**: Limpo, filtro e transformo os dados, preparando-os para análise. Utilizo SQL e Pandas para transformar e normalizar as tabelas.
3. **Carregamento**: Armazeno os dados processados no banco de dados PostgreSQL, organizado de forma a facilitar consultas analíticas.

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Python 3.9 ou superior
- Pip (gerenciador de pacotes do Python)
- Git (para versionamento e colaboração)
- Docker (para ambiente do banco de dados)

### Passos

1. Clone o repositório:
   
   ```bash
   git clone https://github.com/seu-usuario/football-analytics.git
   cd football-analytics
