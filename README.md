# 📊 Student Performance Prediction — Linear Regression

Este repositório contém um projeto de **Machine Learning (Regressão Linear)** aplicado a um dataset de desempenho de estudantes.

O objetivo é prever a nota de matemática (**math score**) com base em variáveis como gênero, nível de escolaridade dos pais, tipo de almoço e desempenho em outras provas.

Este projeto foi desenvolvido com foco educacional, visando praticar **pipeline de machine learning, pré-processamento, modelagem e avaliação de regressão**.

---

## 🎯 Objetivo do projeto

- Explorar e analisar o dataset de desempenho de estudantes
- Realizar pré-processamento de variáveis categóricas e numéricas
- Construir pipelines de Machine Learning
- Treinar modelos de regressão
- Avaliar performance com métricas apropriadas
- Interpretar a influência das variáveis no desempenho dos alunos

---

## 📁 Organização do projeto

```
├── dados/                 <- Dataset utilizado no projeto
|
├── notebooks/             <- Notebooks de exploração e modelagem
│
│   └── src/               <- Código auxiliar do projeto
│       ├── __init__.py
│       ├── config.py     <- Configurações gerais do projeto (paths, parâmetros)
│       ├── graficos.py   <- Funções de visualização e EDA
│       ├── models.py     <- Definição e configuração dos modelos
│       └── auxiliares.py <- Funções auxiliares (tratamento, métricas, etc.)
|
├── modelos/               <- Modelos treinados e serializados
├── relatorios/            <- Relatórios e outputs analíticos
│   └── imagens/           <- Gráficos e visualizações geradas
|
├── .gitignore
├── LICENSE
├── ambiente.yml           <- Ambiente reprodutível (conda)
├── README.md
```

---

## ⚙️ Configuração do ambiente

Clone o repositório:

```bash
git clone https://github.com/Tiagoeneas12/students_performance
```

Crie o ambiente:

```bash
conda env create -f enviroment.yml
conda activate machine_learning
```

Execute os notebooks na pasta:

```
notebooks/
```

---

## 🧠 Estrutura do pipeline

O projeto segue uma abordagem modular com separação clara de responsabilidades:

- **config.py** → centraliza caminhos e configurações do projeto
- **graficos.py** → funções para visualização e análise exploratória
- **models.py** → definição de modelos de machine learning
- **auxiliares.py** → funções auxiliares (preprocessamento, métricas, etc.)

Essa organização facilita **reuso, manutenção e escalabilidade do projeto**.

---

## 📊 Etapas do projeto

1. Análise exploratória dos dados (EDA)
2. Tratamento de variáveis categóricas e numéricas
3. Engenharia de features (quando aplicável)
4. Divisão treino/teste
5. Construção de pipelines com sklearn
6. Treinamento de modelos
7. Avaliação e comparação de desempenho
8. Interpretação dos resultados

---

## 📈 Modelos utilizados

- Linear Regression
- Dummy Regressor (baseline)
- Outros modelos para comparação (opcional)

---

## 📏 Métricas de avaliação

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📚 Dataset

O dataset contém informações de desempenho de estudantes, incluindo:

- Gênero
- Raça/etnia
- Nível de escolaridade dos pais
- Tipo de almoço
- Curso preparatório
- Notas de matemática, leitura e escrita

---

## 🧠 Objetivo educacional

Este projeto foi desenvolvido para praticar:

- Machine Learning supervisionado (regressão linear)
- Pipelines com scikit-learn
- Pré-processamento de dados
- Organização modular de projetos em Python
- Avaliação e interpretação de modelos

---

## 📄 Licença

Projeto de uso educacional e livre para estudo.

---
