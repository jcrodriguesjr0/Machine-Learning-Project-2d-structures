# 🧪 Cheminformatics ML: Drug-likeness (QED) Prediction

[🇺🇸 English](#english) | [🇧🇷 Português](#português)

---

<a name="english"></a>
## 🇺🇸 English Version

This repository contains an exploratory (and currently incomplete) **Machine Learning applied to Drug Discovery** application. The pipeline performs stoichiometric feature extraction using RDKit over molecules from the ZINC database with the goal of predicting pharmacological viability indices.

### 🧠 About the Experiment

The `Machine_Learning_Project_2d_structures.ipynb` notebook is structured to solve a classic computational chemistry prediction problem.

**The developed pipeline focused on:**
1. Loading the `250k_rndm_zinc_drugs_clean_3.csv` dataset filled with SMILES (text representation of chemical structures).
2. Systematic extraction of **Atom-Pair fingerprints (AP)** into bit vectors using the RDKit Cheminformatics library.
3. Transforming this pipeline into a relational Dataset: `x` (binary matrix representing the chemistry) and `y` (`qed` - Quantitative Estimate of Drug-likeness, the prediction target).

*Note: This material serves as an experimental draft built as a proof-of-concept for encoding non-linear information (2D molecules) into predictive matrices.*

### 🛠️ Core Tech Stack

- **Language:** Python
- **Data Science:** Pandas, NumPy, Scikit-Learn
- **Cheminformatics:** RDKit (Chem Module)

### 📌 Project Status

⚠️ **Incomplete (Paused):** The pre-processing phase and generation of the feature matrix (`x`) are complete and isolated. The dependent phase (training the ML models, whether Random Forests or Support Vectors) remains as the logical next step.

This repository proves conceptual domain over advanced data engineering and preprocessing applied to the rigorous pharmacological chemistry field.

---

<a name="português"></a>
## 🇧🇷 Versão em Português

Este repositório contém uma aplicação incompleta e exploratória de **Machine Learning para Descoberta de Fármacos** (*Drug Discovery*). O pipeline realiza extração de *features* estequiométricas utilizando o RDKit sobre moléculas do pacote ZINC com foco em prever índices de viabilidade farmacológica.

### 🧠 Sobre a Experiência

O notebook `Machine_Learning_Project_2d_structures.ipynb` foi estruturado para resolver um problema de predição clássica em química computacional.

**O Flow desenvolvido focava em:**
1. Carregamento do dataset `250k_rndm_zinc_drugs_clean_3.csv` recheado de SMILES (Representação em texto de estruturas químicas).
2. Extração sistemática de **Atom-Pair fingerprints (AP)** num vetor de bits usando a biblioteca Cheminformatics RDkit.
3. Transformação do pipeline em um Dataset relacional `x` (vetor binário representando a química) e `y` (`qed` - Quantitative Estimate of Drug-likeness, que é o alvo da previsão).

*Nota: Esse material constitui um rascunho (draft) experimental construído como teste de validação de conceito para a codificação de informações não lineares (moléculas 2D) para matrizes preditivas.*

### 🛠️ Stack Principal

- **Linguagem:** Python
- **Ciência de Dados:** Pandas, NumPy, Scikit-Learn
- **Cheminformatics:** RDKit (Módulo Chem)

### 📌 Status do Projeto

⚠️ **Incompleto (Em Pausa):** O processamento e geração da matriz de features (`x`) foi concluído e isolado. A fase dependente (treinamento de modelos ML, sejam RandomForest ou Support Vectors) segue como próximo passo.

Este repositório prova domínio conceitual no pre-processamento avançado e engenharia de dados (Data Engineering) aplicados ao rigoroso ramo farmacoquímico.
