# 🧪 Cheminformatics ML: Previsão de Drug-likeness (QED)

Este repositório contém uma aplicação incompleta e exploratória de **Machine Learning para Descoberta de Fármacos** (*Drug Discovery*). O pipeline realiza extração de *features* estequiométricas utilizando o RDKit sobre moléculas do pacote ZINC com foco em prever índices de viabilidade farmacológica.

## 🧠 Sobre a Experiência

O notebook `Machine_Learning_Project_2d_structures.ipynb` foi estruturado para resolver um problema de predição clássica em química computacional.

**O Flow desenvolvido focava em:**
1. Carregamento do dataset `250k_rndm_zinc_drugs_clean_3.csv` recheado de SMILES (Representação em texto de estruturas químicas).
2. Extração sistemática de **Atom-Pair fingerprints (AP)** num vetor de bits usando a biblioteca Cheminformatics RDkit.
3. Transformação do pipeline em um Dataset relacional `x` (vetor binário representando a química) e `y` (`qed` - Quantitative Estimate of Drug-likeness, que é o alvo da previsão).

*Nota: Esse material constitui um rascunho (draft) experimental construído como teste de validação de conceito para a codificação de informações não lineares (moléculas 2D) para matrizes preditivas.*

## 🛠️ Stack Principal

- **Linguagem:** Python
- **Ciência de Dados:** Pandas, NumPy, Scikit-Learn
- **Cheminformatics:** RDKit (Módulo Chem)

## 📌 Status do Projeto

⚠️ **Incompleto (Em Pausa):** O processamento e geração da matriz de features (`x`) foi concluído e isolado. A fase dependente (treinamento de modelos ML, sejam RandomForest ou Support Vectors) segue como próximo passo.

Este repositório prova domínio conceitual no pre-processamento avançado e engenharia de dados (Data Engineering) aplicados ao rigoroso ramo farmacoquímico.
