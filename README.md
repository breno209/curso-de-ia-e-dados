# 🧠 Curso de IA e Dados

### Jornada prática de aprendizado em Python, Análise de Dados e Machine Learning

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Em%20andamento-yellow?style=for-the-badge)]()
[![License](https://img.shields.io/badge/Licença-MIT-green?style=for-the-badge)]()


---

## 📖 Sobre o Repositório

Este repositório reúne meu percurso de estudos em **Inteligência Artificial, Ciência de Dados e Python**, construído aula a aula em formato de **notebooks Jupyter**. Aqui documento desde os fundamentos da linguagem Python — variáveis, tipos de dados e lógica — até etapas mais avançadas como **manipulação de dados com bibliotecas especializadas**, **tratamento e limpeza de bases reais** e **construção de modelos de Machine Learning**.

Mais do que um repositório de exercícios, este espaço funciona como um **diário técnico de aprendizagem**: cada notebook representa uma aula, um conceito consolidado e uma etapa concluída rumo à proficiência em dados e IA.

> 💡 **Objetivo principal:** transformar teoria em prática, aplicando cada conceito estudado em código real, com dados reais, de forma incremental e reproduzível.

---

## 🗂️ Estrutura do Projeto

```
curso-de-ia-e-dados/
│
├── 📁 data/                          # Bases de dados brutas utilizadas nas aulas
│
├── 🐍 app.py                         # Fundamentos de Python (variáveis, tipos, print)
│
├── 📓 aula02.ipynb                   # Aula 02 — Introdução prática (Notebook)
├── 📓 exercicios_aula02.ipynb        # Exercícios de fixação da Aula 02
├── 📓 aula03.ipynb                   # Aula 03 — Estruturas e lógica de programação
├── 📓 aula04.ipynb                   # Aula 04 — Manipulação e análise de dados
├── 📓 aula06.ipynb                   # Aula 06 — Tópicos avançados de dados
│
├── 📚 bibliotecas.ipynb              # Estudo das principais bibliotecas de dados em Python
├── 🤖 ml.ipynb                       # Introdução prática a Machine Learning
│
├── 📊 base_estudantes_tratado.csv    # Dataset de estudantes já limpo e tratado
│
└── 📄 README.md                      # Este documento
```

---

## 🧭 Trilha de Aprendizado

O conteúdo foi organizado para seguir uma progressão natural de conhecimento — dos fundamentos da linguagem até a construção de modelos preditivos:

| Etapa | Módulo | Descrição | Principais Conceitos |
|:---:|---|---|---|
| 01 | `app.py` | Fundamentos de Python | Variáveis, tipos de dados (`int`, `str`, `float`), `print()`, `type()` |
| 02 | `aula02.ipynb` + `exercicios_aula02.ipynb` | Prática guiada + exercícios | Lógica de programação, fixação de conceitos |
| 03 | `aula03.ipynb` | Estruturas de dados e controle de fluxo | Listas, condicionais, laços de repetição |
| 04 | `aula04.ipynb` | Manipulação de dados | Estruturação, leitura e exploração inicial de datasets |
| 05 | `bibliotecas.ipynb` | Ecossistema de dados em Python | Pandas, NumPy e ferramentas de análise |
| 06 | `aula06.ipynb` | Tratamento e engenharia de dados | Limpeza, transformação e preparação de bases |
| 07 | `base_estudantes_tratado.csv` | Dataset aplicado | Resultado prático do tratamento de dados reais |
| 08 | `ml.ipynb` | Machine Learning | Modelagem preditiva, treino e avaliação de modelos |

---

## 🛠️ Tecnologias e Ferramentas

<div align="center">

| Categoria | Ferramentas |
|---|---|
| **Linguagem** | Python 3.10+ |
| **Ambiente** | Jupyter Notebook / JupyterLab |
| **Manipulação de Dados** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn |
| **Visualização** | Matplotlib / Seaborn *(conforme aplicável nas aulas)* |
| **Controle de Versão** | Git & GitHub |

</div>

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- [Python 3.10+](https://www.python.org/downloads/) instalado
- [Git](https://git-scm.com/) instalado
- (Opcional) [Ambiente virtual](https://docs.python.org/3/library/venv.html) configurado

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/breno209/curso-de-ia-e-dados.git

# 2. Acesse a pasta do projeto
cd curso-de-ia-e-dados

# 3. (Recomendado) Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows

# 4. Instale as dependências principais
pip install jupyter pandas numpy scikit-learn matplotlib seaborn

# 5. Inicie o Jupyter Notebook
jupyter notebook
```

Após iniciar o Jupyter, basta abrir qualquer um dos arquivos `.ipynb` e executar as células em sequência para acompanhar o passo a passo de cada aula.

---

## 📊 Sobre a Base de Dados

O arquivo [`base_estudantes_tratado.csv`](./base_estudantes_tratado.csv) representa o resultado prático das técnicas de **limpeza e tratamento de dados** aplicadas ao longo do curso — incluindo tratamento de valores ausentes, padronização de colunas e ajustes de tipos — servindo como insumo para as etapas de análise exploratória e modelagem preditiva presentes em `ml.ipynb`.

---

## 🎯 Objetivos de Aprendizagem

- ✅ Consolidar a lógica de programação em Python
- ✅ Dominar bibliotecas essenciais para análise de dados
- ✅ Aplicar técnicas de limpeza e tratamento de dados em bases reais
- ✅ Construir e avaliar modelos de Machine Learning
- ✅ Desenvolver uma base sólida para projetos de Ciência de Dados e IA

---

## 🗺️ Roadmap

- [x] Fundamentos de Python
- [x] Estruturas de dados e lógica de programação
- [x] Introdução às bibliotecas de dados (Pandas/NumPy)
- [x] Tratamento e limpeza de dados reais
- [x] Primeiros modelos de Machine Learning
- [ ] Modelos avançados de ML (classificação, regressão, clustering)
- [ ] Visualização de dados avançada (dashboards)
- [ ] Introdução a Deep Learning
- [ ] Projeto final aplicado

---

## 🤝 Contribuições

Este é um repositório de estudos pessoais, mas sugestões, correções e boas práticas são sempre bem-vindas! Sinta-se à vontade para abrir uma [issue](https://github.com/breno209/curso-de-ia-e-dados/issues) ou enviar um [pull request](https://github.com/breno209/curso-de-ia-e-dados/pulls).

---

## 📜 Licença

Este projeto está sob a licença MIT — sinta-se livre para estudar, adaptar e reutilizar o conteúdo, mantendo os devidos créditos.

---


### 👤 Autor

**Breno209**
Estudante e entusiasta de Inteligência Artificial e Ciência de Dados

[![GitHub](https://img.shields.io/badge/GitHub-breno209-181717?style=for-the-badge&logo=github)](https://github.com/breno209)

---

*"Dados são o novo petróleo — mas só têm valor quando refinados com conhecimento."*

⭐ Se este repositório te ajudou de alguma forma, deixe uma estrela!
