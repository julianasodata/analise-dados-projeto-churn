# Análise de Dados: Identificação de Churn 📉

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** detalhada para identificar padrões de cancelamento de clientes (Churn). O diferencial desta abordagem é o foco na **higienização automatizada**, garantindo que a base de dados esteja livre de ruídos antes de qualquer modelagem preditiva.

## 🎯 Objetivo do Projeto

Transformar dados brutos em informações confiáveis. O projeto ataca diretamente o problema de inconsistência de dados (como valores não-numéricos em campos de faturamento) que frequentemente enviesam análises de retenção em empresas de tecnologia e serviços.

## 🚀 Destaques Técnicos

O projeto implementa uma lógica de **Data Quality** através da função customizada `invalidos(df)`, que executa:

* **Tipagem Dinâmica:** Identifica e separa automaticamente o tratamento de colunas categóricas e numéricas.
* **Detecção de Ruído com Coerção:** Utiliza `pd.to_numeric(errors='coerce')` para localizar strings camufladas em colunas de valor, algo comum em exportações de sistemas ERP.
* **Relatório de Inconsistências:** Resume o volume de erros por coluna, permitindo uma decisão rápida sobre o descarte ou tratamento de registros.

## 📁 Estrutura do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| `Projeto_Ciencia_Dados.ipynb` | Notebook principal com a lógica de análise e limpeza. |
| `Imagem_Projeto_Ciencia_Dados_2.jpg` | Asset visual integrado ao relatório via IPython Display. |

## 🛠️ Tecnologias e Ferramentas

* **Pandas & Numpy**: Processamento, limpeza e manipulação matricial de dados.
* **IPython.display**: Utilizado para renderizar interfaces e elementos visuais diretamente no notebook.

## ⚙️ Como Executar

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/julianasodata/analise-dados-projeto-churn.git](https://github.com/julianasodata/analise-dados-projeto-churn.git)
   ```
   
2. **Instale as dependências:**
   ````bash
   pip install pandas numpy
   ````
3. **Inicie o ambiente:**
   Abra o arquivo .ipynb utilizando o Jupyter Notebook, VS Code ou importe para o Google Colab.

## 🔮 Próximos Passos

* [ ] Implementação de visualizações gráficas de distribuição com `Seaborn`.
* [ ] Aplicação de modelos de Machine Learning (Random Forest ou XGBoost) para predição.
* [ ] Tratamento estatístico de *outliers* identificados durante a EDA.

---
**Desenvolvido por [Juliana Santos](https://www.linkedin.com/in/julianasodata)**

> "Transformando dados em decisões estratégicas."
   
