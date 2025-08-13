# Tratamento de Dados e Big Data

Projeto desenvolvido como parte do curso de **Analista de Dados** da EBAC, focado em **tratamento, limpeza e análise de grandes volumes de dados** utilizando **Python** e **PySpark**.

## 📌 Objetivo
O projeto foi dividido em duas partes principais:

1. **Tratamento e Limpeza de Dados Diversos**  
   - Consultas e limpeza em conjuntos de dados variados (clientes, pedidos, produtos, etc.).
   - Aplicação de boas práticas de ETL (Extract, Transform, Load) para organização e padronização dos dados.

2. **Análise e Tratamento de Dados do YouTube**  
   - Processamento de dados sobre vídeos, canais e métricas de engajamento.
   - Tratamento de inconsistências e valores ausentes.
   - Preparação dos dados para análises futuras.

## 🛠 Tecnologias Utilizadas
- **Python 3**
- **PySpark**
- Bibliotecas auxiliares:
  - `pandas`
  - `pyspark.sql`
  - `numpy`

## 📂 Estrutura do Repositório
```
/
├── Definicao_Coleta_Dados.zip      # Primeira etapa do projeto (coleta e definição de dados)
├── Tratamento_Dados.zip            # Scripts e arquivos de tratamento de dados diversos
├── Projeto_Youtube/                # Pasta dedicada ao processamento e análise dos dados do YouTube
│   ├── dados/                      # Arquivos de dados utilizados
│   ├── notebooks/                  # Jupyter Notebooks do projeto
│   └── scripts/                    # Scripts em Python e PySpark
└── README.md                       # Documento de descrição do projeto
```

## 🚀 Como Executar
1. **Clonar o repositório**  
   ```bash
   git clone https://github.com/CMichelin07/Tratamentos_Dados_e_BIG-DATA.git
   cd Tratamentos_Dados_e_BIG-DATA
   ```

2. **Instalar dependências**  
   Certifique-se de ter o **Python 3** e o **PySpark** instalados:
   ```bash
   pip install pandas numpy pyspark
   ```

3. **Executar os scripts ou notebooks**  
   - Para executar no PySpark, utilize:
     ```bash
     spark-submit script.py
     ```
   - Ou abra os notebooks no Jupyter:
     ```bash
     jupyter notebook
     ```

## 📊 Resultados
- Conjuntos de dados limpos e prontos para análise.
- Padronização de colunas e tipos de dados.
- Tratamento de valores ausentes e inconsistências.
- Dados do YouTube processados para insights futuros.

## 📄 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para utilizá-lo e adaptá-lo.
