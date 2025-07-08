# 🌱 AgroMart - Especificar a avaliação

## 📘 Introdução

Este documento detalha a **Etapa 2 – Seleção de Métricas** da abordagem Goal-Question-Metric (GQM) para a avaliação da qualidade do software **AgroMart**.  

O foco principal da avaliação é a característica de **Usabilidade**, com atenção especial à experiência de usuários com diferentes níveis de alfabetização digital, conforme definido na Fase 1 do projeto.

O objetivo deste artefato é **formalizar as métricas** que serão utilizadas para responder às questões de medição, garantindo que a coleta de dados seja estruturada, objetiva e alinhada aos objetivos de negócio e qualidade.

---

## 🎯 Abordagem GQM

A avaliação de qualidade do **AgroMart** segue o modelo GQM, que estabelece uma hierarquia clara para medição:

1. **Goal (Objetivo):** O que se deseja alcançar.
2. **Question (Questão):** Questões que caracterizam e avaliam o objeto de estudo.
3. **Metric (Métrica):** Dados e indicadores a serem coletados.

Este documento foca na conexão entre **Questões** e **Métricas**.

---

## 🎯 Objetivo Geral da Medição

**Analisar** a interface do sistema **AgroMart**  
**Para o propósito de** avaliar o uso da ferramenta  
**Com respeito a** critérios de usabilidade  
**Do ponto de vista da** experiência do usuário  
**No contexto de** da disciplina de Qualidade de Software

A partir deste objetivo, foram derivados **dois objetivos específicos**, detalhados a seguir.

---

## 📊 Visão Hierárquica GQM

### 🎯 Objetivo de Medição 1

#### 🔹 Questão Q1  
**Os usuários conseguem distinguir claramente os significados dos ícones e das cores?**  
- M1.1: Taxa de Interpretação Correta de Ícones  
- M1.2: Tempo de Hesitação por Ícone  
- M1.3: Associação Correta de Cores  

#### 🔹 Questão Q2  
**As imagens e cores contribuem para a tomada de decisão?**  
- M2.1: Percepção de Utilidade dos Elementos Visuais  
- M2.2: Eficiência do Caminho da Tarefa  

#### 🔹 Questão Q3  
**Há confusão entre elementos visuais distintos ou sobreposição de funções?**  
- M3.1: Taxa de Erro por Confusão Visual  
- M3.2: Matriz de Confusão de Ícones  

---

### 🎯 Objetivo de Medição 2

#### 🔹 Questão Q4  
**Os feedbacks são percebidos pelos usuários?**  
- M4.1: Taxa de Percepção de Feedback  

#### 🔹 Questão Q5  
**Os sinais do sistema são compreendidos?**  
- M5.1: Taxa de Compreensão das Mensagens  

#### 🔹 Questão Q6  
**Os feedbacks ajudam na navegabilidade?**  
- M6.1: Tempo de Recuperação de Erro  
- M6.2: Avaliação da Utilidade  


---

## 🎯 Objetivo de Medição 1 - Métricas

### 🔹 Questão Q1
**Os usuários conseguem distinguir claramente os significados dos ícones e das cores?**

| ID   | Métrica                           | Detalhes                                                                                                                                         |
|------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| M1.1 | Taxa de Interpretação Correta de Ícones | Coleta: Pergunta ao usuário antes do clique. <br> Escala: Percentual (%) <br> Critério: >90% de acerto em funções críticas.                         |
| M1.2 | Tempo de Hesitação por Ícone      | Coleta: Cronometrar o tempo entre ver e clicar. <br> Escala: Segundos (s) <br> Critério: Média <5s para tarefas comuns.                           |
| M1.3 | Associação Correta de Cores       | Coleta: Perguntar o significado da cor de feedback. <br> Escala: Binário (Correto/Incorreto) <br> Critério: 100% de associação correta.             |

---

### 🔹 Questão Q2
**As imagens e cores contribuem para a tomada de decisão?**

| ID   | Métrica                         | Detalhes                                                                                                                                               |
|------|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| M2.1 | Percepção de Utilidade dos Elementos Visuais | Coleta: Questionário pós-tarefa (1 a 5). <br> Escala: Likert (1-5) <br> Critério: Média >4.0.                                                               |
| M2.2 | Eficiência do Caminho da Tarefa | Coleta: Número de cliques real x caminho ideal. <br> Escala: Razão (Cliques Reais / Ideais) <br> Critério: Razão ≤1.2.                                        |

---

### 🔹 Questão Q3
**Há confusão entre elementos visuais distintos ou sobreposição de funções?**

| ID   | Métrica                        | Detalhes                                                                                                                                  |
|------|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| M3.1 | Taxa de Erro por Confusão Visual | Coleta: Contar cliques errados. <br> Escala: Ocorrências por sessão <br> Critério: ≤1 erro por tarefa crítica.                              |
| M3.2 | Matriz de Confusão de Ícones     | Coleta: Anotar pares de ícones confundidos. <br> Escala: Tabela de frequência <br> Critério: Nenhum par se destacar como fonte de erros.   |

---

## 🎯 Objetivo de Medição 2 - Métricas

### 🔹 Questão Q4
**Os feedbacks são percebidos pelos usuários?**

| ID   | Métrica                       | Detalhes                                                                                                                           |
|------|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| M4.1 | Taxa de Percepção de Feedback | Coleta: Pergunta sobre como soube da conclusão da ação. <br> Escala: Percentual (%) <br> Critério: >95% dos usuários identificam.   |

---

### 🔹 Questão Q5
**Os sinais do sistema são compreendidos?**

| ID   | Métrica                           | Detalhes                                                                                                                       |
|------|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| M5.1 | Taxa de Compreensão das Mensagens | Coleta: Pedir explicação da mensagem. <br> Escala: Percentual (%) <br> Critério: >90% de compreensão correta.                   |

---

### 🔹 Questão Q6
**Os feedbacks ajudam na navegabilidade?**

| ID   | Métrica                      | Detalhes                                                                                                                                           |
|------|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| M6.1 | Tempo de Recuperação de Erro | Coleta: Cronometrar tempo da exibição ao acerto. <br> Escala: Segundos (s) <br> Critério: Tempo médio baixo.                                       |
| M6.2 | Avaliação da Utilidade       | Coleta: Questionário (1 a 5). <br> Escala: Likert (1-5) <br> Critério: Média >4.2.                                                                  |

---

## 🧩 Critérios de Julgamento e Níveis de Pontuação

A tabela abaixo apresenta, **para cada métrica**, a escala utilizada, os níveis de pontuação e o critério de aceitação:

---

### 🔹 Objetivo de Medição 1

| ID   | Métrica                            | Escala         | Níveis de Pontuação                                  | Critério de Aceitação                                        |
|-------|------------------------------------|-----------------|-----------------------------------------------------|--------------------------------------------------------------|
| M1.1 | Taxa de Interpretação Correta      | Percentual (%)  | 0–69 = Ruim<br>70–89 = Regular<br>≥90 = Bom         | ≥90% de acertos em ícones críticos                          |
| M1.2 | Tempo de Hesitação por Ícone       | Segundos (s)    | >10 = Ruim<br>5–10 = Regular<br><5 = Bom            | Média inferior a 5 segundos                                 |
| M1.3 | Associação Correta de Cores        | Binário         | 0 = Incorreto<br>1 = Correto                        | 100% de associações corretas                                |
| M2.1 | Percepção de Utilidade Visual      | Likert (1–5)    | ≤2 = Ruim<br>3 = Regular<br>≥4 = Bom                | Média superior a 4.0                                         |
| M2.2 | Eficiência do Caminho da Tarefa    | Razão           | >1.5 = Ruim<br>1.2–1.5 = Regular<br>≤1.2 = Bom      | Razão menor ou igual a 1.2                                   |
| M3.1 | Taxa de Erro por Confusão Visual   | Ocorrências     | ≥3 = Ruim<br>2 = Regular<br>≤1 = Bom                | No máximo 1 erro por tarefa crítica                         |
| M3.2 | Matriz de Confusão de Ícones       | Frequência      | Pares com alta frequência (>30%) = Ruim            | Nenhum par deve ser fonte primária de confusão              |

---

### 🔹 Objetivo de Medição 2

| ID   | Métrica                            | Escala         | Níveis de Pontuação                                  | Critério de Aceitação                                        |
|-------|------------------------------------|-----------------|-----------------------------------------------------|--------------------------------------------------------------|
| M4.1 | Taxa de Percepção de Feedback      | Percentual (%)  | 0–79 = Ruim<br>80–94 = Regular<br>≥95 = Bom         | ≥95% identificam feedback                                   |
| M5.1 | Taxa de Compreensão das Mensagens  | Percentual (%)  | 0–79 = Ruim<br>80–89 = Regular<br>≥90 = Bom         | ≥90% de compreensão correta                                 |
| M6.1 | Tempo de Recuperação de Erro       | Segundos (s)    | >15 = Ruim<br>6–15 = Regular<br>≤5 = Bom            | Tempo médio baixo indica feedback eficaz                   |
| M6.2 | Avaliação da Utilidade do Feedback | Likert (1–5)    | ≤2 = Ruim<br>3 = Regular<br>≥4 = Bom                | Média superior a 4.2                                        |

---

## 👥 Tabela de Contribuição

| 🎓 Matrícula | 🙋 Nome completo | 📊 Contribuição (%) |
|-------------|------------------|---------------------|
| 211030765 | [Guilherme Storch de Oliveira](https://github.com/storch7) | 16.66 |
| 222037610 | [Gabriel Lima da Silva](https://github.com/gabriel-lima258) | 16.66 |
| 222022000 | [Milena Fernandes Rocha](https://github.com/MilenaFRocha) | 16.66 |
| 222025324 | [João Lucas Araujo Siqueira](https://github.com/jlucasiqueira) | 16.66 |
| 222015248 | [Rafael Gomes Pereira](https://github.com/rafgpereira) | 16.66 |
| 222015112 | [Gabriel Reis Scheidt Paulino](https://github.com/Gxaite) | 16.66 |

---


## 📅 Histórico de Versões

| 📌 Versão | 📆 Data | ✍️ Descrição | 👤 Autor | 🔍 Revisor |
|:--------:|:-------|:-------------|:--------|:-----------:|
|`1.0`| 26/06/2025| Criação da documentação |[Gabriel Lima](https://github.com/gabriel-lima258)| [Guilherme Storch](https://github.com/storch7) |
|`1.1`| 05/07/2025| Artefato preenchido com as devidas informações |[Milena Rocha](https://github.com/milenafrocha)| [Guilherme Storch](https://github.com/storch7) |
