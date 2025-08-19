# 📊 Análise de Evasão de Clientes - Telecom X

### 🚀 Propósito da Análise

O objetivo deste projeto é investigar e identificar os principais fatores que contribuem para a alta taxa de evasão de clientes (*churn*) na empresa de telecomunicações **Telecom X**. Através do processo de ETL (Extração, Transformação e Carga) e de uma análise exploratória de dados (EDA), o projeto busca extrair insights valiosos para subsidiar a equipe de *Data Science* na criação de modelos preditivos e estratégias de retenção de clientes.

Este repositório contém os passos completos da análise, desde o tratamento dos dados brutos até a visualização das descobertas mais relevantes.

### 📁 Estrutura do Projeto

A organização dos arquivos e a estrutura do projeto seguem as boas práticas de análise de dados.

```
.
├── TelecomX_Data.json
├── TelecomX_dicionario.md
├── TelecomX_BR (projetoFinal).ipynb
└── README.md (este arquivo)
```

  * `TelecomX_Data.json`: O conjunto de dados original, contendo informações de clientes em formato JSON aninhado.
  * `TelecomX_dicionario.md`: Um arquivo de texto com a descrição de cada coluna no conjunto de dados.
  * `TelecomX_BR (projetoFinal).ipynb`: O notebook Jupyter que contém todo o código para o processo de ETL, a análise exploratória e a geração dos gráficos.
  * `README.md`: Este arquivo de documentação, explicando o projeto e como executá-lo.

### 🧠 Exemplos de Gráficos e Insights

A análise exploratória revelou padrões críticos de evasão. A seguir, alguns exemplos de visualizações e os *insights* obtidos:

**1. Proporção de Evasão de Clientes**

  * **Insight:** A análise inicial demonstra que a taxa de *churn* é de **26.5%**. Este número elevado ressalta a urgência de uma intervenção estratégica para reter a base de clientes.

**2. Evasão por Tipo de Contrato**

  * **Insight:** O gráfico de barras mostra que clientes com **contratos mensais** são a principal fonte de evasão. Eles representam a maior parte dos clientes que deixam a empresa, enquanto clientes com contratos de um ou dois anos tendem a permanecer fiéis.

**3. Distribuição de Meses de Contrato (Tenure)**

  * **Insight:** O histograma de *tenure* revela que a maior parte da evasão ocorre nos **primeiros 10-15 meses** de contrato. Clientes com maior tempo de permanência na empresa são significativamente mais leais.

### 💻 Instruções para Executar o Notebook

Para replicar a análise, siga os passos abaixo:

1.  **Pré-requisitos:** Certifique-se de ter o Python instalado (versão 3.8 ou superior) e o Jupyter Notebook ou, preferencialmente, utilize o Google Colab para uma execução mais simples.

2.  **Preparação dos Arquivos:**

      * Faça o download ou clone este repositório.
      * No Google Colab, clique no ícone de pasta à esquerda e faça o upload dos arquivos `TelecomX_Data.json` e `TelecomX_BR (projetoFinal).ipynb`.

3.  **Execução:**

      * Abra o notebook `TelecomX_BR (projetoFinal).ipynb` no seu ambiente preferido.
      * Execute as células de código sequencialmente, de cima para baixo. As instruções e comentários no notebook guiarão você por todo o processo.

-----

📧 **Contato:** Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato.
