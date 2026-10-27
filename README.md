# 🏥 Dashboard de Telemetria e Gestão de Operações Clínicas

Este projeto consiste em um dashboard gerencial dinâmico desenvolvido em **Power BI** para monitoramento em tempo real da jornada do paciente, controle de eficiência operacional e análise de gargalos de atendimento (SLA) em uma unidade de saúde.

## 📸 Visualização do Projeto
![Dashboard Preview](dashboard.png)

## 🎯 Problema de Negócio Resolvido
Uma clínica médica multiplataforma enfrentava problemas de ociosidade de equipes médicas e reclamações recorrentes sobre o tempo de espera na recepção. Este painel foi estruturado como um "Gêmeo Digital" operacional para dar visibilidade imediata aos gestores sobre a volumetria diária e o tempo que cada profissional leva para iniciar o atendimento.

## 📊 Indicadores Chave de Performance (KPIs) & Inteligência de Dados
O projeto utiliza **Medidas DAX Explícitas** para garantir performance e escalabilidade:
*   **Volumetria Total (`Total_Atendimentos`):** Contagem distinta de pacientes únicos para controle de tráfego na unidade.
*   **SLA de Atendimento (`Tempo_Medio_Espera`):** Monitoramento do tempo médio em minutos que os pacientes aguardam na recepção.
*   **Otimização de Capacidade:** Gráfico de rosca dinâmico cruzando volumetria analítica por profissional de saúde para identificar sobrecarga ou ociosidade.

## 🛠️ Tecnologias e Técnicas Aplicadas
*   **Power BI Desktop:** Modelagem de dados, extração e design de interface.
*   **Linguagem DAX:** Desenvolvimento de métricas de negócio customizadas.
*   **User Experience (UX/UI):** Design baseado em *Dark Mode* para reduzir a fadiga visual em salas de controle operacional.
*   **Engenharia de Dados Básica:** Limpeza, tipagem e tratamento de dados nulos (pacientes aguardando) via Power Query.
