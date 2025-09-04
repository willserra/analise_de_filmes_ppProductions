# Desafio Cientista de Dados — PProductions

## 🎬 Objetivo
Este projeto foi desenvolvido como parte do desafio da Indicium, com o objetivo de **analisar um dataset cinematográfico** e responder a perguntas de negócio estratégicas para o estúdio fictício *PProductions*. Além da análise exploratória (EDA), foi construído um modelo de **Machine Learning** para prever a nota do IMDB de um filme, com base em variáveis estruturais e textuais.

---

## 📂 Estrutura do Repositório
```
LH_CD_William_S_Serra/
├── data/
│   └── desafio_indicium_imdb.csv   # Dataset original
├── notebooks/
│   └── LH_CD_William_S_Serra.ipynb # Notebook principal com EDA e ML
├── reports/
│   └── Relatorio LH_CD_William_S_Serra.pdf              # Relatório em PDF 
├── models/
│   └── imdb_rating_predictor_full.pkl          # Modelo treinado e salvo
├── requirements.txt                            # Pacotes necessários para execução
└── README.md                                   # Este arquivo
```

---

## ⚙️ Instalação
### Usando Google Colab (recomendado)
1. Faça upload do repositório ou conecte com seu Google Drive.  
2. Abra o arquivo `LH_CD_William_S_Serra.ipynb` no Colab.  
3. Instale os pacotes necessários:
```bash
!pip install -r requirements.txt
```

### Usando ambiente local (Python ≥ 3.9)
1. Clone este repositório:
```bash
git clone https://github.com/willserra/LH_CD_William_S_Serra.git
cd LH_CD_William_S_Serra
```
2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```
3. Instale os pacotes:
```bash
pip install -r requirements.txt
```
4. Abra o notebook:
```bash
jupyter notebook notebooks/LH_CD_William_S_Serra.ipynb
```

---

## ▶️ Execução
- **Exploração dos dados (EDA):** basta rodar o notebook do início ao fim para reproduzir todos os gráficos, estatísticas e insights.  
- **Relatório:** uma versão em PDF do notebook já está disponível em `reports/Relatorio LH_CD_William_S_Serra.pdf`.  
- **Treinamento do modelo:** o pipeline completo está implementado no notebook; ao final, o modelo é salvo em `models/imdb_rating_predictor_full.pkl `.  
- **Inferência:** há um exemplo no notebook mostrando como carregar o modelo `.pkl` e prever a nota IMDB de um novo filme.

---

## 📊 Principais Entregas
1. **EDA Completa**: tratamento de dados, estatísticas descritivas, correlações, análises por gênero/diretor/ator, insights de texto (`Overview`).  
2. **Respostas às Perguntas do Desafio**: recomendações de filmes, fatores de sucesso, insights de overview, possibilidade de inferir gênero.  
3. **Modelo Preditivo**: regressão para prever `IMDB_Rating`, com validação e métricas de performance (RMSE, MAE).  
4. **Relatório**: versão final em PDF consolidando toda a análise.  

---

## 🛠️ Tecnologias Utilizadas
- **Python 3.9+**
- Bibliotecas: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `wordcloud`, `vaderSentiment`
- **Google Colab** para execução em nuvem
- **Jupyter Notebook** para desenvolvimento local

---

## 👤 Autor
William S. Serra — Projeto entregue como parte do processo seletivo Lighthouse / Indicium.
