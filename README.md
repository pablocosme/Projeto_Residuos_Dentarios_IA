### Triagem Virtual de Compostos Vegetais com Potencial de Nucleação de Hidroxiapatita em Dentina Desmineralizada

---

## Sobre o Projeto

A falha em restaurações dentárias, frequentemente associada à cárie secundária e à degradação da interface adesiva, permanece um desafio crítico na odontologia restauradora. A remineralização da dentina exige não apenas íons cálcio e fosfato, mas também moléculas capazes de atuar como **análogos biomiméticos** — ligando-se à matriz de colágeno exposta e guiando a nucleação de cristais de **hidroxiapatita (HAp)**.

Embora compostos sintéticos e derivados animais (como os fosfopeptídeos de caseína) sejam amplamente estudados, o vasto repertório de **compostos orgânicos de origem vegetal** — polifenóis, flavonoides e fitopeptídeos — permanece subexplorado, apesar do seu reconhecido potencial na reticulação do colágeno e da sua baixa toxicidade.

Este projeto aplica **Machine Learning (Random Forest)** para realizar uma triagem virtual desse espaço químico, transformando o paradigma de "descoberta acidental" em **design de materiais guiado por dados**.

---

## Objetivo

Desenvolver um modelo preditivo capaz de classificar compostos orgânicos vegetais como **mineraliza** ou **não mineraliza** de hidroxiapatita em dentina desmineralizada, com base em descritores físico-químicos moleculares — acelerando a identificação de candidatos para validação experimental.

---

## Tecnologias

- **Python** — linguagem principal
- **Scikit-learn** — Random Forest, validação cruzada
- **Pandas / NumPy** — manipulação de dados
- **Matplotlib / Seaborn** — visualização

---

## Dados

O dataset foi construído a partir de mineração manual de literatura odontológica, consolidando resultados experimentais de testes de remineralização (microdureza, EDX, microscopia eletrônica) de substâncias já validadas. A variável-alvo é binária: `1` (mineraliza) / `0` (não mineraliza).

> ⚠️ Dataset em curadoria ativa. Colaboração clínica: **Dra. Elvia Maria Campos** (Cirurgiã - Dentista).

---

## Contexto Acadêmico

Projeto desenvolvido no âmbito de **mestrado em Odontologia / Ciência de Materiais**, na interface entre quimioinformática e odontologia restauradora. Orientado por abordagem interdisciplinar entre IA e bancada laboratorial.

---

*"A IA não substitui o laboratório — ela decide para onde apontar o microscópio."*
