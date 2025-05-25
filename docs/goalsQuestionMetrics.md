# Objetivo do negócio AGROMART

Melhorar a experiência do usuário (UX/UI), com foco especial na inclusão de agricultores com baixa alfabetização textual e digital, por meio de interfaces simples, acessíveis, visuais e intuitivas, garantindo que mesmo usuários semi-analfabetos ou com pouca familiaridade com tecnologia consigam utilizar a plataforma com autonomia e confiança.

| | |
|---|---|
|Analisa| a interface do sistema AGROMART |
|para o propósito de| avaliar o uso da ferramenta |
|com respeito a| critérios de usabilidade |
|de ponto de vista da| experiência do usuário |
|No contexto de| uma disciplna de Qualidade de Software. |

# Questões objetivo de medição

##  Objetivo 1: Reduzir barreiras textuais na interface

### Perguntas

| ID | Pergunta                                                                                                                                                      |
| -- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Q1 | Os elementos visuais da interface (ícones, imagens e cores) são compreensíveis e suficientes para permitir a navegação sem a necessidade de leitura de texto? |
| Q2 | As imagens utilizadas representam corretamente as ações ou informações que pretendem transmitir?                                                              |
| Q3 | A disposição dos elementos na tela facilita a identificação de caminhos e ações sem depender da leitura textual?                                              |


### Diagrama:

### Abstraction Sheet

| **Object**                      | Plataforma digital avaliada                                                                                                  |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**                     | Avaliar o impacto da quantidade de texto sobre a usabilidade                                                                 |
| **Quality Focus**               | Clareza textual, sobrecarga cognitiva                                                                                        |
| **Viewpoint**                   | Usuários com baixa alfabetização textual                                                                                     |
| **Quality Focus**               | - Relação texto vs imagem<br>- Dificuldade relatada<br>- Frequência de erros                                                 |
| **Variation Factors**           | - Quantidade de texto<br>- Uso de linguagem técnica<br>- Presença de ilustrações                                             |
| **Baseline Hypotheses**         | - Interfaces com mais imagens têm 40% menos erros<br>- Interfaces com linguagem simplificada reduzem pedidos de ajuda em 50% |
| **Impact of Variation Factors** | Mais elementos visuais e linguagem simples facilitam a compreensão e reduzem erros                                           |

---

##  Objetivo 2: Verificar a compreensão dos elementos visuais

### Perguntas

| ID | Pergunta                                                                                       |
| -- | ---------------------------------------------------------------------------------------------- |
| Q4 | Os usuários conseguem distinguir claramente os significados dos ícones e das cores utilizadas?|
| Q5 | As imagens e cores contribuem para a tomada de decisão durante a navegação?                    |
| Q6 | Há confusão entre elementos visuais com significados distintos ou sobreposição de funções?     |


### Diagrama

![Diagrama](./assets/diagrama2.png)

### Abstraction Sheet

| **Elemento**                    | **Descrição**                                                                                                                                                                                           |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Object**                      | Interface gráfica (telas e ícones)                                                                                                                                                                      |
| **Purpose**                     | Avaliar se os elementos visuais (ícones, cores, imagens) são compreendidos de forma intuitiva pelos usuários                                                                                            |
| **Quality Focus**               | - Interpretação correta de ícones e cores<br>- Facilidade de navegação com base nos elementos visuais<br>- Taxa de cliques corretos<br>- Solicitações de ajuda<br>- Tempo para concluir tarefas visuais |
| **Baseline Hypotheses**         | - Ícones familiares reduzem o tempo de navegação em até 30%<br>- Falta de padrão visual aumenta a taxa de erro em até 60%<br>- Elementos visuais bem contrastados melhoram a precisão em 25%            |
| **Variation Factors**           | - Design e familiaridade dos ícones<br>- Consistência visual entre telas<br>- Uso de padrões visuais universais<br>- Paleta de cores e contraste                                                        |
| **Impact of Variation Factors** | - Elementos consistentes aumentam a autonomia do usuário<br>- Redução nos erros de navegação<br>- Maior satisfação e sensação de controle                                                               |
                     

---

##  Objetivo 3: Avaliar a clareza dos feedbacks do sistema

### Perguntas

| ID | Pergunta                                                                                 |
| -- | ---------------------------------------------------------------------------------------- |
| Q7 | Os feedbacks visuais (como mudanças de cor ou animações) são percebidos pelos usuários?  |
| Q8 | Os sinais sonoros ou alertas são compreendidos em termos de significado e ação esperada? |
| Q9 | Os feedbacks ajudam os usuários a corrigir seus próprios erros durante o uso do sistema? |


### Diagrama

### Abstraction Sheet

| **Object**                      | Respostas da interface após ações do usuário                                                |
| ------------------------------- | ------------------------------------------------------------------------------------------- |
| **Purpose**                     | Verificar se o sistema comunica corretamente o que está acontecendo                         |
| **Quality Focus**               | Clareza e pontualidade dos feedbacks                                                        |
| **Viewpoint**                   | Usuários que não compreendem mensagens de erro técnicas                                     |
| **Quality Focus**               | - Presença de mensagens claras<br>- Feedback visual/sonoro por ação                         |
| **Variation Factors**           | - Uso de linguagem simples<br>- Tipos de feedback (visuais, sonoros)                        |
| **Baseline Hypotheses**         | - Feedback com ícones reduz dúvidas em 50%<br>- Feedback ausente gera frustração e abandono |
| **Impact of Variation Factors** | Feedback claro e imediato aumenta confiança e reduz abandono de tarefas                     |


---

##  Objetivo 4: Promover o uso autônomo e confiante da plataforma

### Perguntas

| ID  | Pergunta                                                                                                            |
| --- | ------------------------------------------------------------------------------------------------------------------- |
| Q10 | Os usuários conseguem concluir tarefas básicas (como cadastrar, buscar, acessar conteúdos) sem assistência externa? |
| Q11 | Os usuários relatam confiança e conforto ao utilizar a plataforma após um breve período de uso?                     |
| Q12 | Existem pontos da navegação que geram frustração, hesitação ou abandono da tarefa por parte do usuário?             |


### Diagrama

### Abstraction Sheet

| **Object**                      | Plataforma durante tarefas completas                                                                        |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Purpose**                     | Avaliar se os usuários conseguem usar o sistema sozinhos                                                    |
| **Quality Focus**               | Grau de autonomia e confiança do usuário                                                                    |
| **Viewpoint**                   | Agricultores com baixa familiaridade digital                                                                |
| **Quality Focus**               | - Tempo para completar tarefas<br>- Nível de satisfação<br>- Necessidade de auxílio externo                 |
| **Variation Factors**           | - Complexidade da navegação<br>- Padrões de interação<br>- Personalização e acessibilidade                  |
| **Baseline Hypotheses**         | - Interfaces simples aumentam em 60% o uso sem ajuda<br>- Interfaces complexas elevam a taxa de desistência |
| **Impact of Variation Factors** | Menor complexidade e melhor acessibilidade aumentam a confiança e o sucesso na execução de tarefas          |

---

## Tabela de Contribuição

<div align="center">
  <table border="1">
    <thead>
      <tr>
        <th>Matrícula</th>
        <th>Nome completo</th>
        <th>Contribuição (%)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>211030765</td>
        <td><a href="https://github.com/storch7">Guilherme Storch de Oliveira</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222037610</td>
        <td><a href="https://github.com/gabriel-lima258">Gabriel Lima da Silva</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222022000</td>
        <td><a href="https://github.com/MilenaFRocha">Milena Fernandes Rocha</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222025324</td>
        <td><a href="https://github.com/jlucasiqueira">João Lucas Araujo Siqueira</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222015248</td>
        <td><a href="https://github.com/rafgpereira">Rafael Gomes Pereira</a></td>
        <td>19</td>
      </tr>
      <tr>
        <td>222015112</td>
        <td><a href="https://github.com/Gxaite">Gabriel Reis Scheidt Paulino</a></td>
        <td>19</td>
      </tr>
    </tbody>
  </table>
</div>

---

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|22/05/2025|Criação da página inicial|[Gabriel Lima](https://github.com/gabriel-lima258)| [Guilherme Storch](https://github.com/storch7) |
|`1.1`|25/05/2025|Criação da tabela de contribuição|[Guilherme Storch](https://github.com/storch7)| |
