# Avaliação de Modelos de Machine Learning para Previsão de Resultados no Futebol ⚽️🤖

Este projeto tem como objetivo avaliar modelos de Machine Learning para prever o resultado de partidas de futebol (Vitória do Time da Casa, Vitória do Visitante ou Empate).

## 👨‍💻 Autor
Matheus Graça Lira

## 🧠 Modelos Avaliados
- Random Forest (com parâmetros padrão e com ajuste via GridSearchCV)
- XGBoost

## 🏁 Resultados
- **Random Forest (padrão)**: 79,47% de acurácia
- **Random Forest (com tuning)**: 79,51% de acurácia
- **XGBoost**: testado como alternativa, visando melhoria de performance

## 🛠️ Pré-processamento
- Label Encoding em colunas categóricas
- Padronização dos dados com `StandardScaler`
- Transformação da variável alvo (`WIN`) em valores numéricos

## 📁 Arquivos
- `avaliacao_machine_matheus.ipynb`: notebook com todo o código do projeto
- `requirements.txt`: bibliotecas necessárias para rodar o projeto

## ▶️ Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/futebol-ml-avaliacao.git
   cd futebol-ml-avaliacao
