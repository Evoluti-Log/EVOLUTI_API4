# 📌 MVP - Desenvolvimento de um dashboard interativo com dados agregados de segurança viária, permitindo análises comparativas entre estados e indicadores de risco em todo o território nacional

## 🎯 Objetivo do MVP

- O objetivo deste MVP é desenvolver uma ferramenta que integre dados públicos provenientes de diferentes fontes — PRF, DATASUS, DENATRAN e IBGE — para analisar de forma abrangente os indicadores de sinistralidade no trânsito no Brasil. A proposta do MVP é unificar essas bases em uma única plataforma, permitindo a visualização de métricas por estado e em nível nacional.

- Ao centralizar e facilitar o acesso a esses indicadores, o sistema visa aprimorar a compreensão sobre os fatores que influenciam a sinistralidade e contribuir para ações mais eficazes de prevenção e redução de acidentes.

- A hipótese que será validada com o MVP é que a integração de múltiplas bases públicas de dados em uma plataforma de BI facilita a análise e interpretação das informações sobre sinistros de trânsito, promovendo maior eficiência na elaboração de políticas públicas e estratégias de segurança viária.

---

## 📝 Descrição da Solução
 
- O MVP incluirá funcionalidades básicas, inicialmente utilizando o RENAEST como base de dados, além de um painel interativo (dashboard) que mostrará informações como, localidade, acidentes, vítimas e tipos de veículos.

- De início, filtramos as bases dos últimos 5 anos do RENAEST.
  
- O escopo deste MVP será propositalmente reduzido para validar a ideia com o mínimo necessário. A prioridade será apresentar dados do RENAEST com visualizações simples, mas que já ajudem a entender melhor a realidade do trânsito no Brasil.
---

## 👥 Personas / Usuários-Alvo
- **Analista de dados:** Representado pelo coodernador Marcus Vinícius Nascimento
  
- **Gestor do projeto:** Representado por Carlos Bastos 
---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como analista de dados, quero importar os dados do RENAEST, para ter informações atualizadas sobre acidentes de trânsito.        | Alta       | 5 pontos   |
| US2 | Como analista de dados, quero identificar e remover registros duplicados para garantir a integridade dos dados.         | Média      | 8 pontos   |
| US3 | Como analista de dados, quero padronizar os campos de data, localidade e tipo de acidente para facilitar a análise.        | Média       | 5 pontos   |
| US4 | Como analista de dados, quero aplicar filtros nos dados do RENAEST dentro do sistema de BI para que eu possa realizar analises mais especificas e customizadas, filtrando as informações de acordo com os dados da base.         | Alta      | 8 pontos   |
| US5 | Como analista de dados, quero visualizar o número de acidentes por localidade, para identificar regiões com maior risco.        | Alta       | 5 pontos   |
| US6 |Como gestor do projeto, quero consultar os tipos de veículos mais envolvidos em acidentes.    | Alta      | 8 pontos   |
| US7 | Como gestor do projeto, quero acessar o número de vítimas em acidentes por cidade.        | Alta       | 8 pontos   |
| US8 |Como analista de dados, quero comparar dados de acidentes por localidade ao logo dos últimos 5 anos. | Alta      | 8 pontos   |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Base de dados RENAEST.                        | Concluído|
| 02     | Dashboard com funcionalidades básicas.        | Concluído |
| 03     | Filtros com informações sobre localidade, acidentes, vítimas e tipos de veículos.      | Concluído |


---

## 📊 Critérios de Aceitação
- No primeiro gráfico mostraremos a quantidade de acidente por mês e ano.  
- Número de acidentes por Unidades Federativas.  
- Filtros com os tipos de acidentes, condições metereológicas e fases do dia.  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
![shared image (3)](https://github.com/user-attachments/assets/53978041-584f-4c06-8967-7a1591a63f4a)

