# 🌱 AgroMart - Executar a avaliação

## Introdução 

Na etapa final, os dados foram efetivamente coletados, analisados e comparados com os critérios de julgamento previamente estabelecidos. Essa fase também exigiu que a equipe identificasse oportunidades de melhoria com base nos resultados obtidos. Além disso, foi requerida a execução de pelo menos uma ação de melhoria, justificada com base nas evidências coletadas. As soluções propostas poderiam variar desde alterações técnicas no código até melhorias na usabilidade ou na documentação. Esta fase fizemos entrevista com usuário de perfil de Migrante Digital.

---

## Integrantes que atuaram no desenvolvimento do artefato

Esta tabela inicial terá somente os artefatos de alta relevância que cada integrante do projeto desenvolveu. A contribuição **completa** encontra-se ao final do artefato.

<font size="3"><p style="text-align: center">_Tabela de Participantes_</p></font>


| Nome | Função |
| :--- | :--- |
| [Rafael Gomes](https://github.com/rafgpereira) | Autor da Entrevista|
| [Usuário Anônimo](https://github.com/arthurlleite) | Entrevistado do Artefato |

---

## Gravação da Entrevista 

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/yYrbvesH9Xc?si=4X8NPEKHtV9RY0TZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

---

## 🎯 Objetivo 1: Compreensão dos Elementos Visuais

### M1.1 - Taxa de Interpretação Correta de Ícones

| Ícone           | Correto? | Incorreto | Situação |
|----------------|----------|-------------|-------------|
| Home           | ✘ |   | ✅ Atingido  |
| Pesquisa       |   | ✘ | 🔴 Crítico | 
| Perfil         | ✘ |   | ✅ Atingido  |
| Histórico      |   | ✘ | 🔴 Crítico  |
| Foto Região    |   | ✘ | ✅ Atingido  | 
| Meus dados     | ✘ |   | 🔴 Crítico  |
| Meus endereços |   | ✘ | 🔴 Crítico  |
| Meus planos    |   | ✘ | 🔴 Crítico  |
| Sair           |   | ✘ | 🔴 Crítico  |
| Notificações   |   | ✘ | 🔴 Crítico  |
| Carrinho       | ✘ |   | ✅ Atingido  |
| Whatsapp       |   | ✘ | 🔴 Crítico  |
| **Total**      |**4/12**|**8/12**| **0.33%**  |

### 🧾 Conclusão da Etapa M1.1

A avaliação da interpretação dos ícones revelou **baixo desempenho geral** por parte do usuário. Apenas **4 dos 12 ícones** foram corretamente compreendidos, resultando em uma taxa de acerto de **33%**. Este índice é **significativamente abaixo do ideal**, especialmente em um sistema que visa atender usuários com diferentes níveis de alfabetização digital.

Dos 12 ícones avaliados:
- **8 foram classificados como críticos (🔴)**, por não terem sido interpretados corretamente. Isso inclui ícones com funções essenciais como *Histórico*, *Meus dados*, *Endereços*, *Sair* e *Carrinho*.
- Apenas **4 ícones atingiram o objetivo esperado (✅)**, sugerindo que a representação visual desses foi mais intuitiva para o participante.
- A presença de ícones mal interpretados em áreas centrais da navegação indica um risco direto à **eficiência e autonomia do usuário** no uso da plataforma.

---

### 📌 Recomendações

- **Redesenho ou substituição dos ícones críticos**, priorizando padrões visuais universalmente reconhecíveis.
- **Teste A/B com variações visuais**, como ícones acompanhados de rótulos (texto) para reforçar a função.
- **Inclusão de tutoriais visuais ou onboarding interativo**, especialmente nas primeiras utilizações do app.
- Repetição do teste com **amostra maior de usuários**, a fim de validar se o problema é generalizado ou isolado.

Essa métrica evidencia um dos pontos mais sensíveis da usabilidade da plataforma e deve ser tratada com prioridade no próximo ciclo de melhorias.

---

### M1.2 - Tempo de Hesitação por Ícone

Esta métrica teve como objetivo medir o tempo de hesitação do usuário entre visualizar um ícone e clicar nele, indicando o quão intuitiva é a interface. De acordo com o critério estabelecido (tempo médio inferior a **5 segundos** para tarefas comuns), os resultados foram:

| Tarefa                                                                 | Tempo (s) |
|------------------------------------------------------------------------|-----------|
| Acesse seus endereços a partir da tela de Perfil                      | 37        |
| Acesse seu histórico de compras                                       | 3         |
| Na tela de busca, acesse apenas os mercados de Ceilândia             | 8         |


---

### 📊 Análise

- **Tempo médio observado**: (37 + 3 + 8) / 3 = **16 segundos**
- Apenas **1 das 3 tarefas** ficou dentro do limite recomendado de 5s.
- A tarefa com maior tempo (37s) indica forte dificuldade de localização ou reconhecimento do ícone correspondente.

---

### 📌 Conclusão

O tempo médio ficou muito acima do critério estabelecido, apontando para uma **baixa eficiência cognitiva na identificação dos ícones**. A tarefa mais longa coincide com uma das que também teve maior índice de erro na métrica M1.1, o que reforça o diagnóstico de que a interface não está sendo clara ou familiar o suficiente.

---

### ✅ Recomendações

- **Revisar o design dos ícones mais críticos**, principalmente aqueles que geraram maior hesitação e erros.
- **Testar variações com rótulos textuais ou animações introdutórias**, ajudando na memorização da função dos ícones.
- Avaliar a criação de um **modo de acessibilidade guiada** para os usuários com menor familiaridade digital.
  
---

### M1.3 - Associação Correta de Cores

Esta métrica avaliou a capacidade do usuário de associar corretamente cores comuns da interface a seus significados usuais em contexto de feedback. O critério de aceitação exige **100% de associação correta** para ser considerado satisfatório.

| Cor         | Correta? | Justificativa do Usuário           |
|-------------|----------|------------------------------------|
| Verde (+)   | ✔        | Indica algo positivo/adicionar     |
| Vermelho (-)| ✔        | Indica erro/remover                |

---

### 📊 Análise

- O participante foi capaz de interpretar corretamente os significados das cores **verde** e **vermelha**, com justificativas compatíveis com os padrões de design esperados.
- A interpretação correta indica uma boa **aderência aos princípios de design universal** aplicados ao sistema.

---

### 📌 Conclusão

A métrica foi **atingida com sucesso** (100% de acertos), sugerindo que o uso das cores no sistema está **alinhado com o senso comum dos usuários** e não gera ambiguidade quanto ao seu significado. Esse é um **ponto positivo da interface**, que pode ser mantido como padrão visual nos demais componentes da aplicação.

---

### ✅ Recomendações

- **Manter o padrão cromático atual**, especialmente o uso de verde para ações positivas e vermelho para alertas ou erros.
- **Reaproveitar essas cores em outros elementos críticos**, reforçando a coerência visual e cognitiva da interface.

---

### M2.1 - Percepção de Utilidade Visual

Esta métrica avaliou, por meio de questionário pós-tarefa, o quanto os elementos visuais (imagens e cores) foram percebidos como úteis para a realização das atividades no sistema. O critério de aceitação exige uma **média superior a 4.0** na escala Likert (1 a 5).

> **Nota atribuída pelo participante**: 3

---

### 📊 Análise

- A nota atribuída ficou **abaixo do valor mínimo esperado**, indicando uma **percepção limitada da utilidade dos elementos visuais** por parte do usuário.
- Embora o sistema utilize imagens e cores, elas não foram percebidas como fortemente contributivas para a tomada de decisão ou navegação.

---

### 📌 Conclusão

A avaliação desta métrica sugere que os **elementos visuais não estão sendo suficientemente eficazes ou informativos** para o público-alvo. Isso pode indicar que as imagens utilizadas não são representativas ou que o contraste/estilo das cores não está otimizando a experiência de uso.

---

### ✅ Recomendações

- **Reavaliar as imagens utilizadas**, optando por conteúdos mais representativos, com foco em usuários de baixa alfabetização.
- **Otimizar o uso de cores** para indicar estados, categorias ou ações, reforçando sua função comunicativa.
- Considerar **testes qualitativos complementares** (ex: entrevistas curtas) para entender o que não foi percebido como útil.

---

### M2.2 - Eficiência do Caminho da Tarefa

Esta métrica analisou a relação entre o número de cliques realizados pelo usuário e o número ideal necessário para completar uma tarefa. O critério de aceitação define que a **razão real/ideal deve ser menor ou igual a 1.2**.

| Tarefa                                                                       | Cliques Reais | Cliques Ideais | Razão |
|------------------------------------------------------------------------------|----------------|----------------|--------|
| Encontre um mercado, adicione dois produtos e faça o pedido                 | 20             | 10             | 2,0    |
| Acesse o histórico e depois os detalhes de um pedido                        | 2              | 2              | 1,0    |

---

### 📊 Análise

- A tarefa de acesso ao histórico foi realizada com **eficiência ótima (razão 1.0)**.
- A tarefa de compra apresentou **razão de 2.0**, excedendo significativamente o critério de aceitabilidade.
- O resultado indica que, em tarefas mais complexas, o caminho percorrido pelo usuário foi **mais que o dobro do ideal**, demonstrando dificuldades de navegação, redundâncias ou confusão na interface.

---

### 📌 Conclusão

A eficiência do caminho da tarefa varia bastante de acordo com a complexidade da atividade. Enquanto tarefas simples são cumpridas com eficiência, tarefas mais completas exigem **muitos cliques adicionais**, o que compromete a usabilidade e pode gerar frustração.

---

### ✅ Recomendações

- **Revisar a arquitetura de navegação**, especialmente nas etapas de compra.
- **Reduzir o número de etapas/clicks** por meio de agrupamento funcional, atalhos ou automações.
- Considerar **mapas de calor ou gravações de sessões** em testes futuros para identificar pontos de dispersão ou indecisão.

---

### M3.1 e M3.2 - Erros e Confusão Visual

As métricas M3.1 e M3.2 têm como objetivo identificar **erros de navegação causados por confusão visual** e mapear os **ícones ou elementos mais frequentemente confundidos**.

| Tarefa                                                        | Erros/Confusões |
|---------------------------------------------------------------|-----------------|
| Acesse seus endereços a partir da tela de Perfil              | Tocou no mercado, imagem do perfil na home, título "Home" e nome do usuário |

---

### 📊 Análise

- Durante a execução de **uma única tarefa**, o participante cometeu pelo menos **quatro cliques errôneos**, indicando confusão significativa.
- Os erros envolvem **múltiplos elementos com aparência ou localização semelhante**, como imagem do perfil, nome do usuário e o próprio título "Home".
- O volume e a diversidade de erros violam o critério de M3.1 (≤1 erro por tarefa crítica) e indicam um **agrupamento de elementos confusos**, conforme apontado na métrica M3.2.

---

### 📌 Conclusão

A análise conjunta destas métricas aponta para **um grave problema de clareza visual e organização da interface**. Elementos visuais próximos ou com funções distintas estão gerando **interpretações ambíguas**, prejudicando a experiência do usuário e aumentando o tempo de execução das tarefas.

---

### ✅ Recomendações

- **Redesenhar a tela inicial e a seção de perfil**, destacando com mais clareza os pontos de entrada para cada funcionalidade.
- **Aplicar testes A/B com variações de layout**, visando reduzir a sobreposição visual e semântica dos elementos.
- **Adicionar rótulos textuais temporários ou persistentes** para reforçar a diferenciação entre componentes com aparência semelhante.
- Reforçar o uso de **padrões de design consistentes** entre ícones e suas funções reais.

---

## 🎯 Objetivo 2: Clareza dos Feedbacks do Sistema

### M4.1 e M5.1 - Percepção e Compreensão de Feedbacks

As métricas M4.1 e M5.1 avaliam, respectivamente, se os usuários percebem os feedbacks emitidos pelo sistema e se compreendem corretamente seu significado.

| Ação Realizada  | Percebeu Feedback? | Compreendeu Mensagem? |
|------------------|---------------------|------------------------|
| Finalizar compra | Não                 | Não                   |
| Alterar nome     | Sim                 | Sim                    |
| Alterar endereço | Sim                 | Sim                    |

---

### 📊 Análise

- **Percepção de feedbacks (M4.1)**: 2 de 3 ações foram percebidas → **66,7%**
- **Compreensão das mensagens (M5.1)**: 2 de 3 mensagens foram compreendidas corretamente → **66,7%**

---

### 📌 Conclusão

Os resultados demonstram que **as taxas estão abaixo dos critérios de aceitação**:
- M4.1 exige >95% de percepção
- M5.1 exige >90% de compreensão

O feedback da ação mais crítica ("Finalizar compra") não foi percebido nem compreendido, o que evidencia uma **falha significativa na comunicação de ações concluídas com sucesso**, comprometendo a segurança e confiança do usuário durante o processo de navegação.

---

### ✅ Recomendações

- **Reforçar os feedbacks visuais e auditivos** em ações críticas, como finalizações de pedidos.
- **Utilizar animações, pop-ups mais evidentes ou notificações persistentes** para garantir que o usuário perceba a conclusão de uma ação.
- Realizar **testes A/B com diferentes estilos de feedback**, avaliando impacto na taxa de percepção e compreensão.

---

### M6.1 e M6.2 - Recuperação de Erro e Utilidade do Feedback

Estas métricas avaliaram se o feedback do sistema foi útil para ajudar o usuário a **recuperar-se de um erro** e se essa ajuda foi percebida como clara e eficaz.

| Tarefa                                  | Tempo de Recuperação (s) | Nota de Utilidade (1 a 5) |
|----------------------------------------|----------------------------|----------------------------|
| Adicionar endereço com valor inválido  | 6                          | 4                          |

---

### 📊 Análise

- O **tempo de recuperação** foi de **6 segundos**, o que não é crítico, mas também **não é considerado um tempo "baixo"** — especialmente se o erro for recorrente.
- A **nota de utilidade** ficou em **4**, abaixo do critério estabelecido (>4.2), indicando que o feedback foi útil, mas **não plenamente satisfatório**.

---

### 📌 Conclusão

Apesar de o usuário ter conseguido corrigir o erro, os dados indicam que **a mensagem de erro poderia ser mais objetiva, rápida ou visível**. O sistema auxilia, mas ainda exige certo esforço do usuário para entender o problema e corrigi-lo, o que pode impactar negativamente a fluidez da navegação.

---

### ✅ Recomendações

- **Melhorar a clareza e visibilidade das mensagens de erro**, utilizando linguagem simples e direta.
- **Incluir sugestões automáticas de correção ou preenchimento** ao lado dos campos com erro.
- Investir em **design de microinterações** mais evidentes (animações, bordas em vermelho, ícones informativos) que direcionem o usuário diretamente ao campo com problema.
  
---

## 📌 Conclusão e Próximos Passos

Esta avaliação analisou diversas métricas de usabilidade com foco na compreensão visual, feedback do sistema e eficiência das tarefas. Abaixo segue uma **síntese geral dos resultados**, com **classificação por prioridade de intervenção**:

---

## 🔴 Prioridade Máxima

🔹 **M1.1 - Interpretação de Ícones (33% de acertos)**  
Ícones fundamentais foram interpretados erroneamente, gerando confusão e impactando a navegação.  
✅ Ação recomendada: Redesenho dos ícones e adição de rótulos.

🔹 **M3.1/M3.2 - Confusão Visual e Erros**  
Usuário clicou em vários elementos incorretos tentando realizar uma tarefa simples.  
✅ Ação recomendada: Revisar o layout e separar claramente elementos próximos.

🔹 **M4.1/M5.1 - Feedback Não Percebido/Compreendido (66,7%)**  
Feedbacks críticos (como finalizar compra) passaram despercebidos ou não foram compreendidos.  
✅ Ação recomendada: Destacar visualmente os feedbacks com pop-ups mais evidentes.

---

## 🟠 Prioridade Média

🔸 **M2.2 - Eficiência do Caminho (razão 2.0 para tarefa de compra)**  
Caminhos longos e ineficientes prejudicam a experiência.  
✅ Ação recomendada: Reduzir etapas e cliques necessários.

🔸 **M6.1/M6.2 - Tempo de Recuperação e Utilidade do Feedback**  
O feedback de erro ajudou, mas demorou e não foi considerado excelente.  
✅ Ação recomendada: Tornar mensagens mais claras e destacar o campo com erro.

🔸 **M2.1 - Utilidade dos Elementos Visuais (nota 3)**  
Imagens e cores não foram percebidas como úteis o suficiente.  
✅ Ação recomendada: Usar elementos visuais mais representativos e direcionados ao público.

---

## 🟢 Prioridade Baixa

🟢 **M1.3 - Associação de Cores (100% de acerto)**  
As cores foram corretamente associadas aos seus significados.  
✅ Ação recomendada: Manter padrão atual.

---

## 🧩 Considerações Finais

A avaliação revelou **problemas críticos de interpretação visual e percepção de feedback**, especialmente nas tarefas mais importantes para o fluxo da aplicação. Há um potencial expressivo de melhoria ao **refinar ícones, simplificar caminhos, e tornar os feedbacks mais evidentes e acessíveis**. O uso correto das cores é um ponto positivo que pode ser ampliado.

**Próximos passos recomendados:**
- Redesenho e testes A/B para ícones e telas críticas.
- Reestruturação dos fluxos de tarefa com foco em eficiência.
- Reforço na comunicação de feedbacks e mensagens de erro.

---

## 🛠️ Propostas de Melhoria Baseadas nas Métricas Avaliadas

Com base nas evidências coletadas por meio da entrevista e avaliação de métricas, foram propostas as seguintes **ações de melhoria**, agrupadas por tipo de intervenção:

---

### 🎨 Interface e Usabilidade (Alto Impacto)

🔹 **Redesenho dos Ícones Críticos e Inclusão de Rótulos Textuais**

* Justificativa: 66% dos ícones não foram compreendidos corretamente (M1.1), impactando diretamente a autonomia do usuário.
* Ação: Desenvolver novo conjunto de ícones baseados em bibliotecas reconhecidas (Material Icons, FontAwesome), com rótulos curtos visíveis (ex: "Meus Planos").
* Execução: Protótipo de alta fidelidade criado no Figma e adicionado ao repositório.


<div align = center >
<p>Protótipo da página de Perfil</p>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/4XQSUk7Vbct20J9Up3vcpc/Untitled?node-id=13-24&embed-host=share" allowfullscreen></iframe>
</div>

🔹 **Refatoração da Tela de Perfil e Navegação Inicial**

* Justificativa: A métrica M3.2 revelou múltiplos erros de navegação causados por sobreposição visual.
* Ação: Reorganizar os elementos da tela de perfil em seções distintas, com espaçamento, ícones mais intuitivos e textos auxiliares.

<div align = center >
<p>Protótipo da página Home</p>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/4XQSUk7Vbct20J9Up3vcpc/Untitled?node-id=3-931&embed-host=share" allowfullscreen></iframe>
</div>

🔹 **Criação de Onboarding Guiado e Dicas Visuais**

* Justificativa: Tempo de hesitação alto (M1.2) e nota baixa na utilidade visual (M2.1).
* Ação: Desenvolver um tutorial interativo que apareça nas primeiras utilizações, explicando funções básicas com tooltips.

---

### 📣 Comunicação de Feedback (Alto Impacto)

🔸 **Melhoria nos Feedbacks de Ação Crítica (ex: Finalizar Compra)**

* Justificativa: Usuário não percebeu nem compreendeu o feedback ao finalizar a compra (M4.1 e M5.1).
* Ação: Criar modal de confirmação com animação, mensagem clara (“Compra finalizada com sucesso!”) e botão de retorno visível.

<div align = center >
<p>Protótipo da página de Feedback</p>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/4XQSUk7Vbct20J9Up3vcpc/Untitled?node-id=3-899&embed-host=share" allowfullscreen></iframe>
</div>

🔸 **Melhoria nas Mensagens de Erro**

* Justificativa: Embora útil, a mensagem de erro foi considerada pouco clara e exigiu tempo de recuperação (M6.1/M6.2).
* Ação: Reformular os textos das mensagens, adicionar sugestões automáticas (ex: “Insira um CEP válido”) e destacar o campo com borda vermelha e ícone de atenção.

---



## ✅ Ação Executada

**Ação escolhida**: Desenvolvimento de um **protótipo de alta fidelidade com redesenho da tela de perfil e melhoria dos ícones principais**, incorporando rótulos e feedbacks visuais.

**Motivação**: A escolha foi baseada na **gravidade dos erros visuais detectados (M1.1, M3.1/M3.2)** e na necessidade urgente de **melhorar a compreensão dos ícones e caminhos de navegação**. Um protótipo permite validar rapidamente as mudanças com os usuários antes da implementação definitiva.

**Ferramenta utilizada**: Figma

**Link para o protótipo**: [Protótipo Figma - Redesign AgroMart](https://www.figma.com/design/4XQSUk7Vbct20J9Up3vcpc/Untitled?node-id=3-899&t=CL82LURE3dqhNNke-0)



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
|`1.1`| 08/07/2025| Adição do Protótipo do Figma |[Milena Rocha](https://github.com/milenafrocha)| [Guilherme Storch](https://github.com/storch7) |