# Análise de Dados e Modelagem Preditiva para Plataforma de Aluguel Temporário em Nova York

## Descrição do Projeto
Bem-vindo ao repositório do projeto de análise de dados e modelagem preditiva para uma plataforma de aluguel temporário em Nova York, desenvolvido como parte do desafio de Ciência de Dados do Programa Lighthouse da Indicium. Este projeto envolve a análise exploratória de dados (EDA) do mercado de aluguel temporário de Nova York, utilizando dados do principal concorrente, com o objetivo de desenvolver uma estratégia de precificação eficaz para o nosso cliente.

## Estrutura do Repositório
- `README.md`: Este arquivo.
- `requirements.txt`: Lista de pacotes Python necessários para executar o projeto.
- `data_dictionary.md`: Dicionário de dados fornecendo detalhes sobre o dataset utilizado.
- `exploratory_data_analysis.ipynb`: Jupyter Notebook com a Análise Exploratória de Dados (EDA).
- `price_prediction_model.ipynb`: Jupyter Notebook com o desenvolvimento do modelo preditivo de preços.
- `model.pkl`: Modelo de previsão de preços salvo em formato pickle.
- `reports/`: Pasta contendo relatórios e gráficos gerados durante a EDA.

## Instalação e Execução
Para executar este projeto, siga os passos abaixo:
1. Clonar o Repositório
```
git clone https://github.com/drisanches/LH_CD_DRIELLY.git ny_model
cd ny_model
```
2. Instalar Dependências
```
pip install -r requirements.txt
```
3. Executar os Jupyter Notebooks  
Abra os notebooks `exploratory_data_analysis.ipynb` e `price_prediction_model.ipynb` em um ambiente que suporte Jupyter Notebook, como o JupyterLab, Goggle Colab ou o VSCode.

## Principais Entregas
- **Análise Exploratória de Dados (EDA):** Investigação detalhada das variáveis disponíveis no dataset, identificação de tendências, padrões e correlações relevantes para o negócio.
- **Modelagem Preditiva:** Desenvolvimento de um modelo de regressão para prever preços de aluguel com base em características do imóvel e localização.
- **Respostas às Questões de Negócio:**
  - Avaliação dos melhores locais para investimento em propriedades para aluguel.
  - Impacto do número mínimo de noites e disponibilidade no preço.
  - Análise de padrões em nomes de anúncios para imóveis de alto valor.
  - Sugestão de preço para um apartamento exemplo com características específicas.

## Tecnologias Utilizadas
- **Python:** Linguagem de programação principal.
- **Pandas, NumPy:** Bibliotecas para manipulação de dados.
- **Matplotlib, Seaborn:** Bibliotecas para visualização de dados.
- **Scikit-learn:** Biblioteca para modelagem preditiva e machine learning.
- **NLTK:** Biblioteca para processamento de linguagem natural.

## Suporte e Contribuições
Para suporte, entre em contato com [driellysanches.s@gmail.com]. Contribuições para o projeto são sempre bem-vindas.
