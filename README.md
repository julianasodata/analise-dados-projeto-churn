# Análise de Dados e Identificação de Inconsistências

Este projeto consiste em uma análise exploratória de dados (EDA) focada na qualidade da informação. O objetivo principal é automatizar a detecção de valores inválidos e preparar datasets para modelos de machine learning ou relatórios de business intelligence.

## 🚀 Funcionalidades do Projeto

O notebook desenvolve uma lógica robusta para:
- **Identificação de Dados Inválidos**: Função customizada que diferencia colunas categóricas de numéricas para encontrar erros de entrada de dados.
- **Visualização Integrada**: Uso de bibliotecas de exibição para contexto visual do projeto.
- **Métricas de Qualidade**: Cálculo do total de inconsistências presentes no dataset.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Python 3
- **Bibliotecas**:
  - `Pandas`: Manipulação e análise de dados.
  - `Numpy`: Suporte para arrays e funções matemáticas.
  - `IPython.display`: Renderização de elementos visuais dentro do notebook.

## 📈 Destaques do Código

Uma parte central do projeto é a função `invalidos(df)`, que percorre o dataframe e:
1. Para **Categorias/Objetos**: Extrai valores únicos para análise de diversidade.
2. Para **Numéricos**: Utiliza máscaras booleanas (`pd.to_numeric`) para identificar caracteres não numéricos em colunas de valores, contabilizando-os como inválidos.

## 📂 Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-projeto.git](https://github.com/seu-usuario/seu-projeto.git)
