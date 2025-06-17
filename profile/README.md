
<p align="center">
  <img src="https://img.shields.io/static/v1?label=Python&message=3.10&color=blue&style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/static/v1?label=Pandas&message=2.x&color=150458&style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/static/v1?label=NumPy&message=1.x&color=013243&style=for-the-badge&logo=numpy"/>
  <img src="https://img.shields.io/static/v1?label=Scikit-Learn&message=1.x&color=f7931e&style=for-the-badge&logo=scikit-learn"/>
  <img src="https://img.shields.io/static/v1?label=TensorFlow&message=2.x&color=FF6F00&style=for-the-badge&logo=tensorflow"/>
  <img src="https://img.shields.io/static/v1?label=Status&message=Em%20Desenvolvimento&color=yellow&style=for-the-badge"/>
  <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
</p>

<h1 align="center">♻️ Classificação de Resíduos Recicláveis</h1>

<p align="center">
  <b>Projeto desenvolvido no Bootcamp em Machine Learning</b> <br>
</p>

---

## 📑 Índice

- [📑 Índice](#-índice)
- [📝 Descrição do Projeto :writing\_hand:](#-descrição-do-projeto-writing_hand)
- [🎯 Objetivo :dart:](#-objetivo-dart)
- [🔥 Atividades do Projeto :fire:](#-atividades-do-projeto-fire)
  - [✅ **ATIV-04-ET-01 — Análise do Dataset**](#-ativ-04-et-01--análise-do-dataset)
  - [✅ **ATIV-04-ET-02 — Pesquisa de Métodos + Propostas**](#-ativ-04-et-02--pesquisa-de-métodos--propostas)
  - [✅ **ATIV-04-ET-03 — Metodologia, Resultados e Conclusões**](#-ativ-04-et-03--metodologia-resultados-e-conclusões)
- [🧠 Pipeline do Projeto :technologist:](#-pipeline-do-projeto-technologist)
- [📊 Dataset :database:](#-dataset-database)
- [🗺️ Estrutura do Projeto](#️-estrutura-do-projeto)
- [📑 Metodologia](#-metodologia)
- [📈 Métricas de Avaliação](#-métricas-de-avaliação)
- [🚀 Como Executar o Projeto :rocket:](#-como-executar-o-projeto-rocket)
  - [1️⃣ Clone este repositório:](#1️⃣-clone-este-repositório)
  - [2️⃣ Acesse a pasta do projeto:](#2️⃣-acesse-a-pasta-do-projeto)
  - [3️⃣ Crie um ambiente virtual:](#3️⃣-crie-um-ambiente-virtual)
  - [4️⃣ Ative o ambiente virtual:](#4️⃣-ative-o-ambiente-virtual)
  - [5️⃣ Instale as dependências:](#5️⃣-instale-as-dependências)
  - [6️⃣ Execute os notebooks ou scripts na pasta `/notebooks` ou `/src`.](#6️⃣-execute-os-notebooks-ou-scripts-na-pasta-notebooks-ou-src)
- [🔧 Tecnologias e Bibliotecas :hammer\_and\_wrench:](#-tecnologias-e-bibliotecas-hammer_and_wrench)
- [👥 Squad :octocat:](#-squad-octocat)
- [📜 Licença :scroll:](#-licença-scroll)

---

## 📝 Descrição do Projeto :writing_hand:

Este projeto tem como objetivo desenvolver um modelo de **Machine Learning e Visão Computacional** capaz de classificar imagens de resíduos recicláveis em diferentes categorias, como papel, vidro, metal, plástico, entre outros.

O desenvolvimento ocorre como parte do **Bootcamp em Machine Learning**, promovendo a aplicação prática dos conceitos aprendidos no curso.

---

## 🎯 Objetivo :dart:

Desenvolver um modelo capaz de **classificar corretamente resíduos recicláveis a partir de imagens**, contribuindo para soluções sustentáveis e inteligentes.

- ✔️ Analisar, preparar e explorar o dataset.
- ✔️ Aplicar modelos da literatura.
- ✔️ Propor melhorias e testar modelos próprios.
- ✔️ Avaliar os modelos usando métricas específicas.
- ✔️ Documentar e apresentar a metodologia, resultados e conclusões.

---

## 🔥 Atividades do Projeto :fire:

### ✅ **ATIV-04-ET-01 — Análise do Dataset**
- ✔️ Verificar integridade dos arquivos.
- ✔️ Checar consistência dos metadados.
- ✔️ Avaliar qualidade das imagens.
- ✔️ Analisar distribuição das classes.
- ✔️ Identificar e tratar imagens duplicadas.

### ✅ **ATIV-04-ET-02 — Pesquisa de Métodos + Propostas**
- ✔️ Implementar e testar métodos da literatura (disponíveis no próprio Kaggle e outros artigos).
- ✔️ Propor melhorias, como:
  - Otimização de hiperparâmetros.
  - Arquiteturas mais leves e rápidas.
  - Redução do conjunto de treino mantendo a performance.

### ✅ **ATIV-04-ET-03 — Metodologia, Resultados e Conclusões**
- ✔️ Documentar a metodologia adotada.
- ✔️ Comparar resultados entre modelos da literatura e modelos próprios.
- ✔️ Apresentar tabelas, gráficos e métricas.
- ✔️ Elaborar conclusões, aprendizados e sugestões de melhorias futuras.

---

## 🧠 Pipeline do Projeto :technologist:

```mermaid
graph TD
A[Análise do Dataset] --> B[Pré-processamento]
B --> C[Modelagem com métodos da literatura]
C --> D[Testes com melhorias e modelos próprios]
D --> E[Análise de Resultados]
E --> F[Conclusões e Entregas]
```

---

## 📊 Dataset :database:

- 📦 **Nome:** Warp Waste Recycling Plant Dataset  
- 🔗 **Link:** [Kaggle - Warp Waste Recycling Plant Dataset](https://www.kaggle.com/datasets/parohod/warp-waste-recycling-plant-dataset)  

**Descrição:**  
O dataset contém imagens categorizadas de resíduos recicláveis, incluindo papel, metal, vidro, plástico, entre outros, utilizadas para treinamento, validação e teste de modelos de classificação de imagens.

---

## 🗺️ Estrutura do Projeto

- `data/` — Dados brutos do dataset.
- `notebooks/` — Notebooks de exploração, modelagem e análise.
- `src/` — Scripts Python utilizados no projeto.
- `outputs/` — Resultados, gráficos e modelos treinados.
- `docs/` — Documentação e apresentações.

---

## 📑 Metodologia

- ✅ **Análise Exploratória dos Dados (EDA)**
- ✅ **Pré-processamento**
- ✅ **Treinamento e Avaliação de Modelos**
- ✅ **Aprimoramento de Modelos (Hiperparâmetros, Arquitetura)**
- ✅ **Análise de Resultados e Conclusões**

---

## 📈 Métricas de Avaliação

- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

---

## 🚀 Como Executar o Projeto :rocket:

### 1️⃣ Clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2️⃣ Acesse a pasta do projeto:

```bash
cd seu-repositorio
```

### 3️⃣ Crie um ambiente virtual:

```bash
python -m venv venv
```

### 4️⃣ Ative o ambiente virtual:

- Windows:

```bash
venv\Scripts\activate
```

- Linux/Mac:

```bash
source venv/bin/activate
```

### 5️⃣ Instale as dependências:

```bash
pip install -r requirements.txt
```

### 6️⃣ Execute os notebooks ou scripts na pasta `/notebooks` ou `/src`.

---

## 🔧 Tecnologias e Bibliotecas :hammer_and_wrench:

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow ou PyTorch
- OpenCV
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👥 Squad :octocat:

<table align="center">
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/ana-sofia-moura-27b003248/">
        <img src="https://avatars.githubusercontent.com/u/109629293?v=4" width="115px;" alt="Ana Sofia Profile Image"/><br>
      </a>
      <sub>
          <b>Ana Sofia Moura</b>
         </sub>
    <br>
        <a href="https://github.com/Sun-cs-Sol">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/ana-sofia-moura-27b003248/">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/usuario-2">
        <img src="https://avatars.githubusercontent.com/u/usuario-2" width="115px;" alt="Elineison de Sousa Profile Image"/><br>
      </a>
      <sub>
          <b>Elineison de Sousa</b>
         </sub>
    <br>
        <a href="https://github.com/usuario-2">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/usuario-2">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/francis-lauriano-9b674a27b/">
        <img src="https://avatars.githubusercontent.com/u/130801505?v=4" width="115px;" alt="Francis Lauriano Profile Image"/><br>
      </a>
      <sub>
          <b>Francis Lauriano</b>
         </sub>
    <br>
        <a href="https://github.com/FrancisLauriano">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/francis-lauriano-9b674a27b/">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/usuario-4">
        <img src="https://avatars.githubusercontent.com/u/usuario-4" width="115px;" alt="Iza Vieira Profile Image"/><br>
      </a>
      <sub>
          <b>Iza Vieira</b>
         </sub>
    <br>
        <a href="https://github.com/usuario-4">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/usuario-4">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/madelu-lopes-089388120/">
        <img src="https://avatars.githubusercontent.com/u/176135579?v=4" width="115px;" alt="Madelu Lopes Profile Image"/><br>
      </a>
      <sub>
          <b>Madelu Lopes</b>
         </sub>
    <br>
        <a href="https://github.com/Mads8760">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/madelu-lopes-089388120/">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
        <td align="center">
      <a href="https://www.linkedin.com/in/usuario-6">
        <img src="https://avatars.githubusercontent.com/u/usuario-6" width="115px;" alt="Mariana Angeli Profile Image"/><br>
      </a>
      <sub>
          <b>Mariana Angeli</b>
         </sub>
    <br>
        <a href="https://github.com/usuario-6">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/usuario-6">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/usuario-7">
        <img src="https://avatars.githubusercontent.com/u/usuario-7" width="115px;" alt="Rodrigo Rocha Profile Image"/><br>
      </a>
      <sub>
          <b>Rodrigo Rocha</b>
         </sub>
    <br>
        <a href="https://github.com/usuario-7">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
        </a>
        <br>
        <a href="https://www.linkedin.com/in/usuario-7">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
        </a>
    </td>
    
  </tr>
</table>

---

## 📜 Licença :scroll:

Este projeto está sob a licença **MIT** — Consulte o arquivo [LICENSE](LICENSE) para mais informações.  

Projeto desenvolvido exclusivamente para fins educacionais no contexto do **Bootcamp em Machine Learning**.

---
