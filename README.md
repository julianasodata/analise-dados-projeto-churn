# Análise de Dados: Identificação de Churn 📉

Este projeto realiza uma Análise Exploratória de Dados (EDA) detalhada para entender os padrões de cancelamento de clientes (Churn). O foco principal é a **higienização e preparação dos dados**, garantindo que as informações estejam prontas para modelos de Machine Learning ou dashboards estratégicos.

## 🎯 Objetivo do Projeto

Identificar comportamentos de clientes e tratar inconsistências no dataset que poderiam enviesar uma análise de retenção. O projeto foca em transformar dados brutos em informações confiáveis através de técnicas avançadas de limpeza.

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Python 3.x
* **Bibliotecas:** * `Pandas`: Manipulação e tratamento de dataframes.
    * `Numpy`: Operações matemáticas e tratamento de arrays.
    * `IPython`: Renderização de elementos visuais no notebook.

## 🚀 Destaques Técnicos

O diferencial deste projeto é a implementação de funções automatizadas para validação de dados, como a função `invalidos(df)`, que:
1.  **Diferencia tipos de dados:** Separa automaticamente colunas de texto (categorias) de colunas numéricas.
2.  **Identificação de Ruído:** Utiliza coerção de tipos (`pd.to_numeric` com `errors='coerce'`) para encontrar caracteres inválidos ou strings em colunas que deveriam ser puramente numéricas.
3.  **Métricas de Qualidade:** Gera um relatório de volume de erros por coluna, essencial para a fase de *Data Cleaning*.

## 📁 Estrutura do Repositório

* `Projeto_Ciencia_Dados.ipynb`: Notebook principal com a análise.
* `Imagem_Projeto_Ciencia_Dados_2.jpg`: Assets visuais utilizados na apresentação do projeto.
* `dataset_exemplo.csv` *(se disponível)*: Base de dados utilizada.

## ⚙️ Como Executar

1. Clone o repositório:
    git clone [https://github.com/julianasodata/analise-dados-projeto-churn.git](https://github.com/julianasodata/analise-dados-projeto-churn.git)

2. Instale as dependências necessárias:
    pip install pandas numpy
    
Execute o Jupyter Notebook ou abra no Google Colab.

*Desenvolvido por Juliana Santos*

---

### Dicas Finais para o seu Portfólio:

1.  **Imagens:** Como seu código tenta carregar uma imagem (`Imagem_Projeto_Ciencia_Dados_2.jpg`), certifique-se de que essa imagem está na **raiz do repositório**. Se ela for apenas decorativa para o notebook, você também pode adicioná-la diretamente no README para dar um visual mais moderno.
2.  **Organização:** No GitHub, vá em **Settings** e certifique-se de que o repositório está **Public**.
3.  **Próximos Passos:** Se você pretende evoluir este projeto, adicione uma seção chamada `## Próximos Passos` citando que pretende aplicar modelos de classificação (como Random Forest ou Regressão Logística) para prever o Churn. Isso mostra que você tem visão de futuro para o projeto.
