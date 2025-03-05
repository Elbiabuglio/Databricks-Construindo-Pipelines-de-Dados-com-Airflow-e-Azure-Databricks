 # 🚀 Databricks-Construindo-Pipelines-de-Dados-com-Airflow-e-Azure-Databricks


 ## 📌 Sobre este projeto

Este repositório contém um guia prático e exemplos de código para explorar e utilizar diversos recursos do Azure Databricks, além de técnicas para extração, transformação e orquestração de dados.



## 🛠️ O que você vai aprender

🔹 Acessar recursos do Azure Databricks e entender como configurar o ambiente.

🔹 Extrair dados de uma API e processá-los para uso em análises.

🔹 Controlar os gastos na Azure, garantindo eficiência e economia no uso dos serviços.

🔹 Escrever arquivos em formatos como Parquet e CSV, otimizando armazenamento e performance.

🔹 Transformar os dados extraídos da API, aplicando técnicas de limpeza e estruturação.

🔹 Criar um bot no Slack para interações automatizadas com seu pipeline.

🔹 Orquestrar todo o pipeline de dados com o Airflow, garantindo automação e monitoramento eficiente.



## 📂 Estrutura do projeto

Databricks-Construindo-Pipelines-de-Dados-com-Airflow-e-Azure-Databricks/


📜├── README.md            # Documentação do projeto

📜├── webserver_config.py  # Configuração do servidor web

📜├── standalone_admin_password.txt  # Senha do administrador (mantenha segura)

📜├── LICENSE              # Licença do projeto

📜├── airflow-webserver.pid # Arquivo PID do servidor Airflow

📜├── airflow.db           # Banco de dados do Airflow

📜├── airflow.cfg          # Configuração do Airflow

📂├── venv/                # Ambiente virtual

│   📂├── bin

|   📂├── include

│   📂├──lib

📂├── notebooks/           # Exemplos práticos

│   ├── 1-extraindo-dados.ipynb

│   └── 2-transformando-dados2.ipynb

│   └── 3-automatizando-relatorio.ipynb

📂├── logs/                # Logs gerados pelo sistema         
                                                                           
│   📂├── dag_id = etl_databricks_pipeline

│   📂├──dag_processor_manager

│   📂├──scheduler

📂├── datAir/              # Diretório específico do projeto ou funcionalidade

│   📂├──bin

│   📂├──generated

│   📂├──include

│   📂├──lib

│   .gitignore              # Arquivo para exclusões no Git

│   lib64

│   pyvenv.cfg              # Configuração do ambiente virtual

📂└── dags/                # DAGs do Airflow

│   📂├── __pycache__      # Diretório para arquivos de cache Python



## 🚀 Como executar este projeto

### Pré-requisitos

Antes de começar, certifique-se de ter:

🔹Uma conta ativa na Azure

🔹Um workspace configurado no Databricks

🔹O Apache Airflow instalado para a orquestração dos processos

🔹Acesso à API de origem dos dados

🔹Um workspace no Slack para criar o bot



## Passos iniciais

1. Clone este repositório:

   git clone https://github.com/seu-usuario/seu-repositorio.git

3. Configure as variáveis de ambiente necessárias.

4. Execute os notebooks do Databricks para testar a extração e transformação dos dados.

5. Configure e inicie o Apache Airflow para orquestrar o pipeline.

6. Configure o bot no Slack e teste a integração.


## 📌 Tecnologias utilizadas

🔹Azure Databricks: Processamento e análise de dados em larga escala.

🔹Apache Airflow: Orquestração e automação do pipeline de dados.

🔹Python: Linguagem principal para extração e transformação de dados.

🔹Parquet & CSV: Formatos para armazenamento otimizado.

🔹Slack API: Comunicação e automação via bot.



## 📄 Licença

Este projeto está licenciado sob a MIT License.
