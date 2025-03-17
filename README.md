### README Profissional

# 📈 Stock Trend Prediction Using Python & Machine Learning

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

## 📝 Descrição

Este projeto é uma aplicação web desenvolvida com **Flask** que utiliza um modelo de **machine learning (LSTM)** para prever tendências de preços de ações. Ele baixa dados históricos do **Yahoo Finance**, processa-os, faz previsões e exibe os resultados em gráficos interativos, como preços de fechamento e médias móveis exponenciais (EMAs). O usuário pode inserir um símbolo de ação ou usar o padrão 'POWERGRID.NS' para explorar os dados.

## 🚀 Funcionalidades

- 🎯 **Previsão de Tendências**: Usa um modelo LSTM pré-treinado para prever preços futuros de ações.
- 📊 **Visualização de Dados**: Gera três gráficos principais:
  - Fechamento vs. Tempo com EMAs de 20 e 50 dias.
  - Fechamento vs. Tempo com EMAs de 100 e 200 dias.
  - Previsão vs. Tendência Original.
- 📥 **Download de Dados**: Permite baixar o dataset processado como arquivo CSV.
- 🖥️ **Interface Web**: Interface simples e amigável para inserção de símbolos de ações e visualização de resultados.

## 📋 Requisitos

Para executar este projeto, você precisará instalar as seguintes bibliotecas Python:

- `Flask`
- `pandas`
- `numpy`
- `matplotlib`
- `pandas_datareader`
- `yfinance`
- `scikit-learn`
- `keras` (para o modelo LSTM)

## 🛠️ Instalação

Siga os passos abaixo para configurar o projeto em sua máquina:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Haell39/stock_price-prediction.git
   ```
2. **Navegue até o diretório**:
   ```bash
   cd stock_price-prediction
   ```
3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Uso

1. Certifique-se de que o modelo LSTM (`stock_dl_model.h5`) está no diretório correto.
2. **Execute a aplicação**:
   ```bash
   python app.py
   ```
3. Acesse `http://127.0.0.1:5000/` no seu navegador.
4. Insira o símbolo da ação desejada (ex.: 'POWERGRID.NS') ou deixe em branco para usar o padrão.
5. Explore os gráficos gerados e baixe o dataset, se desejar.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
