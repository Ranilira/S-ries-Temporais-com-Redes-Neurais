# 📈 Séries Temporais com Redes Neurais LSTM

Projeto de previsão de séries temporais utilizando redes neurais do tipo LSTM (Long Short-Term Memory), desenvolvido como parte da disciplina de Ciência de Dados.

---

## 📋 Descrição

Este projeto aplica técnicas de aprendizado profundo para modelar e prever séries temporais. O pipeline inclui análise exploratória dos dados, pré-processamento, treinamento de uma rede neural LSTM e avaliação dos resultados com métricas de regressão.

---

## 🗂️ Estrutura de Arquivos

```
├── N2_SeriesTemporais_Item40.ipynb  # Notebook principal com todo o pipeline
├── dados_N2.csv                     # Dataset utilizado no projeto
├── requirements.txt                 # Dependências do projeto
├── .gitignore                       # Arquivos ignorados pelo Git
└── README.md                        # Documentação do projeto
```

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **TensorFlow / Keras** — construção e treinamento da rede LSTM
- **Scikit-learn** — pré-processamento e métricas
- **Pandas** — manipulação de dados
- **NumPy** — operações numéricas
- **Matplotlib** — visualização de dados
- **Jupyter Notebook** — ambiente de desenvolvimento

---

## 🚀 Como Instalar e Rodar

### Pré-requisitos

- Python 3.10+ instalado
- Git instalado

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/Ranilira/S-ries-Temporais-com-Redes-Neurais.git
cd S-ries-Temporais-com-Redes-Neurais

# 2. Crie e ative o ambiente virtual
python3 -m venv venv
source venv/bin/activate        # Linux/Mac
# venv\Scripts\activate         # Windows

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Abra o Jupyter Notebook
jupyter notebook
```

### 5. Execute o notebook

Abra o arquivo `N2_SeriesTemporais_Item40.ipynb` e execute as células em ordem.
