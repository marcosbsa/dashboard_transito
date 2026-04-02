# 🚦 Projeto Trânsito — Dashboard de Acidentes em Rodovias Federais

> **Análise de Acidentes, Vítimas e Causas nas Rodovias Federais Brasileiras (PRF) — 2022 e 2023**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Fonte](https://img.shields.io/badge/Fonte-PRF%20(Gov.br)-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ativo-brightgreen?style=for-the-badge)

---
<img width="1410" height="791" alt="dashboard_transito_01" src="https://github.com/user-attachments/assets/259f5e80-6fdd-476f-bc01-f1df17a48608" />
<img width="1411" height="792" alt="dashboard_transito_02" src="https://github.com/user-attachments/assets/5b4989f6-3ad5-447f-a9a9-246fba0f5f0b" />
<img width="1411" height="793" alt="dashboard_transito_03" src="https://github.com/user-attachments/assets/84aa4f61-0783-42d9-9c5a-af0448a269f1" />

---

## 📌 Sobre o Projeto

O **Projeto Trânsito** é um dashboard analítico desenvolvido em Power BI com base nos dados abertos da **Polícia Rodoviária Federal (PRF)**. 
O projeto transforma registros brutos de ocorrências em rodovias federais em **inteligência para políticas públicas de segurança viária**, 
respondendo perguntas críticas sobre onde, quando e por que os acidentes mais graves acontecem.

## 🔗 Acesse o Projeto

https://app.powerbi.com/view?r=eyJrIjoiMWY5OWVkODMtMGEzMS00NDkyLWEyM2UtNTVhOGQ4MzZiN2ZhIiwidCI6IjU1ODQ1MjA3LTk3YjAtNDU4OS1hNjQxLTQ4NGUzNjAxOTlkNyJ9

### 🎯 Objetivos

- Identificar os **estados e rodovias** com maior concentração de acidentes e mortes
- Revelar as **principais causas** de acidentes fatais nas rodovias federais
- Mapear os **horários e dias da semana** de maior risco
- Comparar o comportamento dos acidentes entre **2022 e 2023**
- Apoiar decisões de **fiscalização, infraestrutura e campanhas de prevenção**


## 🗂️ Estrutura dos Dados

| `Dados_PRF` | Fato consolidada | Todos os acidentes (2022 + 2023) com localização, causa, tipo e vítimas |</br>
| `Dados_PRF_2022` | Fato anual | Registros originais de 2022 da PRF |</br>
| `Dados_PRF_2023` | Fato anual | Registros originais de 2023 da PRF |</br>
| `dCalendario` | Dimensão | Calendário completo para análises temporais |</br>


## 📊 KPIs Principais

| Total de Acidentes | Quantidade de ocorrências registradas |</br>
| Total de Mortos | Número de vítimas fatais |</br>
| Total de Feridos | Feridos leves + feridos graves |</br>
| Total de Ilesos | Envolvidos que não sofreram lesões |</br>
| Total de Veículos | Veículos envolvidos nos acidentes |</br>
| Taxa de Mortalidade | Proporção de mortos por acidente |</br>

---

## 💡 Insights Descobertos

### 📈 1. Volume de Acidentes por Ano

| 2022 | 64.547 |</br>
| 2023 | 32.440 |</br>

> Os dados de 2023 cobrem apenas parte do ano — a comparação direta requer atenção ao período analisado.
> O volume de 2022 representa um panorama completo e serve como linha de base para análises futuras.

---

### 🗺️ 2. Estados com Mais Mortes em Rodovias Federais

| MG | 1.044 |</br>
| PR | 833 |</br>
| BA | 780 |</br>
| SC | 526 |</br>
| RS | 513 |</br>

> **Minas Gerais** lidera em mortes absolutas, seguido por Paraná e Bahia.
> SC tem alto volume de acidentes mas menor letalidade proporcional — indicando diferença no **perfil dos acidentes** por estado.

---

### ⚠️ 3. Principais Causas de Mortes

| Transitar na contramão | 1.210 |</br>
| Ausência de reação do condutor | 827 |</br>
| Reação tardia ou ineficiente | 816 |</br>
| Velocidade incompatível | 738 |</br>
| Ultrapassagem indevida | 562 |</br>
| Condutor dormindo | 292 |</br>

> **Transitar na contramão** é a causa com maior taxa de letalidade.
---

### 🚗 4. Tipos de Acidente Mais Fatais

| Colisão frontal | 2.547 |</br>
| Atropelamento de pedestre | 1.280 |</br>
| Saída de leito carroçável | 1.025 |</br>
| Colisão traseira | 831 |</br>
| Colisão transversal | 630 |</br>

> A **colisão frontal** é o tipo mais letal, com quase 40% de taxa de mortalidade por ocorrência.

---

### 🌙 5. Horário e Dia da Semana Mais Perigosos em Número de Acidentes

**Por fase do dia:**

| Plena Noite | 34.055 |</br>
| Pleno Dia | 52.550 |</br>
| Amanhecer | 4.980 |</br>
| Anoitecer | 5.402 |</br>

**Por dia da semana:**

| Domingo | 16.344 |</br>
| Sábado | 16.068 |</br>
| Sexta-feira | 14.910 |</br>

> **Plena noite** concentra menos acidentes que o dia, mas mata mais — sinalizando maior gravidade noturna.
> **O **final de semana (sexta a domingo)** concentra as maiores taxas de mortalidade.

---

## 🧠 Que Tipo de Decisão o Dashboard Ajuda a Tomar?

✅ **Fiscalização:** Concentrar blitzes nos horários e trechos de maior risco (noite, finais de semana)  
✅ **Infraestrutura:** Priorizar melhorias nos estados e rodovias com maior letalidade  
✅ **Campanhas:** Direcionar campanhas de conscientização para as causas mais mortais (contramão, fadiga, velocidade)  

---

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop** — Modelagem e visualização
- **DAX** — Cálculo de métricas e análises temporais
- **Power Query (M)** — Transformação e consolidação dos dados anuais
- **Dados Abertos PRF (Gov.br)** — Fonte oficial dos registros de acidentes

---


## 🔗 Fonte dos Dados

Os dados utilizados são públicos e disponibilizados pela **Polícia Rodoviária Federal** e pela plataforma de Cursos Xperiun
📎 [dados.prf.gov.br](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)

Os dados.csv foram tratados para análise no Power Query antes da modelagem e análise.



