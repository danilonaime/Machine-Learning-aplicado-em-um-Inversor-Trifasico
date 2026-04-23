# Análise de Dados de um Inversor Trifásico para Acionamentos Elétricos

## 📖 Descrição do Projeto
Este projeto tem como foco a análise de dados de um inversor trifásico utilizado em acionamentos elétricos, como motores de indução. A motivação principal baseia-se na técnica de Controle de Campo Vetorial (FOC - *Field-Oriented Control*). 

Como os sensores físicos para medir as tensões de saída do inversor possuem um alto custo, a viabilidade econômica de projetos industriais pode ser impactada. Sendo assim, este trabalho explora e prepara os dados com o intuito de desenvolver um modelo computacional capaz de estimar essas tensões reais através de outros sensores disponíveis, visando reduzir custos sem perdas expressivas no controle desejado.

## 🎯 Objetivo
O objetivo principal desta etapa do projeto é a exploração estatística e o tratamento dos dados visando **obter um modelo capaz de estimar as tensões médias de saída do inversor**, variáveis estas que são utilizadas como parâmetros de controle para o método vetorial (FOC).

## 📊 Sobre o Dataset
O conjunto de dados utilizado foi disponibilizado pelo departamento **LEA (Power Electronics and Electrical Drives)** da **Universidade de Paderborn, Alemanha**. Ele fornece as informações necessárias para a construção do modelo para fins acadêmicos e de pesquisa.

**Destaque da Análise Inicial:** Durante o tratamento bruto, foi constatado que o dataset não possui valores nulos ou faltantes (`NaN`), indicando um pré-tratamento de alta qualidade na origem dos dados.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
O projeto foi desenvolvido em **Python** (Jupyter Notebook), empregando as seguintes ferramentas e bibliotecas:
* **Pandas**: Leitura, manipulação e análise dos dados.
* **NumPy**: Operações matemáticas e manipulação de arrays.
* **Matplotlib & Seaborn**: Construção de gráficos e visualização estatística avançada.
* **Statsmodels**: Criação de modelos e análises estatísticas rigorosas.
* **Scikit-Learn (sklearn)**: Utilizado especificamente para a padronização e escalonamento dos dados (`StandardScaler`).

## 👥 Integrantes da Equipe
* Cleyton Geraldo Paula Maciel
* Danilo Naime Valles Moreira
* Thales da Cunha Tobias

## 📚 Referências
* **Artigo Base**: M. Stender, O. Wallscheid and J. Böcker, *"Data Set Description: Three-Phase IGBT Two-Level Inverter for Electrical Drives,"* Paderborn University, Germany, 2020.
* **Dataset**: M. Stender, O. Wallscheid and J. Böcker, *"Three-phase IGBT two-level inverter for electrical drives (data),"* Kaggle, 2020. [Disponível no Kaggle](https://www.kaggle.com/stender/inverter-data-set).
