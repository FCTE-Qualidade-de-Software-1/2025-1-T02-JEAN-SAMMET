# 1. Desempenho de Processos

## Objetivo 

Monitorar a qualidade do código e da execução das atividades técnicas do projeto.

## Definições

Foram as métricas PSM/CID definidas pelo grupo para execução das atividades das Sprint do projeto final da disciplina de qualidade.

| Atividade| Métrica/Método| Ferramenta | Frequência | 
|----------|---------------|------------|------------|
| Burndown de atividades da equipe | Relação temporal de fechamento das issues ao longo da sprint | GitHub - Zenhub | Ao fim de cada sprint. |
| Tempo médio de resolução de issues | Tempo entre criação e fechamento | GitHub - Zenhub | Ao fim de cada sprint. |
| Taxa de conclusão de tarefas       | (Issues fechadas / planejadas na sprint) * 100%  | GitHub Issues | Ao fim de cada sprint     |

---

## SPRINT 1

<!-- Gráfico de Burndown no topo -->
<canvas id="burndownChart" width="600" height="300"></canvas>

<!-- Container para os dois gráficos lado a lado -->
<div style="display: flex; justify-content: space-between; gap: 20px; margin-top: 40px;">
  <div style="flex: 1;">
    <canvas id="tempoResolucaoChart" width="400" height="300"></canvas>
  </div>
  <div style="flex: 0 0 320px; display: flex; justify-content: center;">
    <canvas id="conclusaoSprintChart" width="300" height="300"></canvas>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  // Gráfico Burndown da Sprint 1
  const ctxBurndown = document.getElementById('burndownChart').getContext('2d');
  const labels = ['25/06', '26/06', '27/06', '28/06', '29/06', '30/06', '01/07', '02/07'];
  const realData = [7, 5, 5, 5, 5, 4, 3, 1];
  const idealData = [];
  const totalTarefas = 9;
  const dias = labels.length;
  for (let i = 0; i < dias; i++) {
    idealData.push((totalTarefas * (dias - 1 - i)) / (dias - 1));
  }
  new Chart(ctxBurndown, {
    type: 'line',
    data: {
      labels: labels,
      datasets: [
        {
          label: 'Ideal',
          data: idealData,
          borderColor: 'rgba(150,150,150,0.5)',
          borderDash: [5, 5],
          fill: false,
        },
        {
          label: 'Real',
          data: realData,
          borderColor: 'rgba(75,192,192,1)',
          backgroundColor: 'rgba(75,192,192,0.2)',
          fill: false,
        }
      ]
    },
    options: {
      responsive: true,
      plugins: {
        legend: { position: 'top' },
        title: { display: true, text: 'Burndown da Sprint 1' }
      },
      scales: {
        y: {
          beginAtZero: true,
          ticks: { stepSize: 1 },
          title: { display: true, text: 'Tarefas Restantes' }
        },
        x: {
          title: { display: true, text: 'Data' }
        }
      }
    }
  });

  // Gráfico Tempo médio de resolução
  const ctxTempo = document.getElementById('tempoResolucaoChart').getContext('2d');
  new Chart(ctxTempo, {
    type: 'bar',
    data: {
      labels: ['Sprint 1'],
      datasets: [{
        label: 'Tempo médio de resolução (dias)',
        data: [0.25],
        backgroundColor: 'rgba(54, 162, 235, 0.6)',
        borderColor: 'rgba(54, 162, 235, 1)',
        borderWidth: 1
      }]
    },
    options: {
      responsive: true,
      plugins: {
        title: {
          display: true,
          text: 'Tempo Médio de Resolução das Issues'
        }
      },
      scales: {
        y: {
          beginAtZero: true,
          max: 2,
          ticks: { stepSize: 0.5 },
          title: { display: true, text: 'Dias' }
        }
      }
    }
  });

  // Gráfico Taxa de Conclusão da Sprint 1 (Doughnut menor)
  const ctxConclusao = document.getElementById('conclusaoSprintChart').getContext('2d');
  new Chart(ctxConclusao, {
    type: 'doughnut',
    data: {
      labels: ['Concluídas', 'Pendentes'],
      datasets: [{
        data: [7, 1],
        backgroundColor: ['rgba(75, 192, 192, 0.7)', 'rgba(255, 99, 132, 0.3)'],
        borderColor: ['rgba(75, 192, 192, 1)', 'rgba(255, 99, 132, 1)'],
        borderWidth: 1
      }]
    },
    options: {
      responsive: true,
      plugins: {
        title: {
          display: true,
          text: 'Taxa de Conclusão da Sprint 1'
        }
      }
    }
  });
</script>

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
|`1.0`|02/07/2025|Criação da documentação |[Guilherme Storch](https://github.com/storch7)| [Guilherme Storch](https://github.com/storch7) |
|1.1| 06/07/2025| Atualização de conteúdo |[Guilherme Storch](https://github.com/storch7)| [Guilherme Storch](https://github.com/storch7) |