# “Mão-na-massa” — Cenário didático: Banco InovaData

## Initiation (Arranque)
**Objetivo:** legitimar o programa e montar a equipa de rollout.  
**Ações-chave:** obter aprovação formal, nomear sponsor executivo(s), formar a equipa (CDO, IT, Negócio, Compliance, Data Stewards).

**Exemplos (InovaData):**
- **Aprovação/charter:** despacho do CEO a nomear a **CDO** e a patrocinar o **PGSD** por 12 meses, com metas trimestrais.
- **Equipa de rollout:** CDO (líder), CIO (co-sponsor), Diretora Comercial (sponsor de negócio), Head de Compliance, 2 Data Stewards (Risco e Retalho).

**Entregáveis rápidos:**
- One-pager de **charter**
- **Organograma** do rollout
- **Calendário de reuniões** (quinzenal sponsors; semanal equipa)

---

## Definition (Definição)
**Objetivo:** alinhar linguagem e “onde a DG atua”.  
**Ações-chave:** definir “o que é DG” e **âmbito** inicial do DM; identificar **unidades alvo**; mapear **capacidades em falta**.

**Exemplos (InovaData):**
- **Definição de DG:** “DG = políticas, papéis e controlos que asseguram qualidade, proteção, conformidade e valor dos dados de **Clientes**, **Contas** e **Crédito**”.
- **Unidades sujeitas:** Comercial (retalho), Operações, Risco & Compliance, TI, Produtos.
- **Capacidades em falta:** catálogo/glossário; processo de **data quality** (regras + monitorização); stewardship formal; gestão de pedidos de dados; registo de linhagem.

**Entregáveis:**
- **Glossário mínimo** (15 termos críticos)
- **Declaração de âmbito** (o que entra/fica fora nos 90 dias)
- Lista de **capacidades alvo** (ex.: Catálogo, DQ, Acesso, Riscos)

---

## Scope (Âmbito)
**Objetivo:** fechar o foco e as restrições com um plano inicial.  
**Ações-chave:** escolher **domínios prioritários**, definir **restrições** (equipa, orçamento, tech), obter **aprovação**.

**Exemplos (InovaData):**
- **Domínios P1 (90 dias):** Clientes e Contas; **P2 (180 dias):** Crédito.
- **Restrições:** 0 FTE novo em TI; usar ferramentas existentes (Power BI, M365) + catálogo leve; tempo máximo de stakeholders em workshops: 2h/semana.
- **Plano inicial:** 6 sprints de 2 semanas, com entregas: **glossário v1 → regras DQ v1 → RACI v1 → catálogo v1 → processo de pedidos de acesso v1**.

**Entregáveis:**
- **Matriz RACI v1** (Owner/Steward/Custodian/CDO/IT/Negócio)
- **Roadmap 90–180 dias**
- **Ata de aprovação** de âmbito

---

## Assessment (Avaliação)
**Objetivo:** medir ponto de partida para orientar esforço de mudança.  
**Ações-chave:** avaliar **maturidade da informação**, **capacidade de mudança (OCM)** e **ambiente de dados** (sistemas/linhagem/riscos).

**Exemplos (InovaData):**
- **Maturidade (rápida):** questionário de 15 itens (DAMA-lite) → resultado: Qualidade = 2/5, Stewardship = 1/5, Segurança = 3/5.
- **Change capacity:** *pulse survey* 5 perguntas (apoio da gestão, tempo disponível, clareza de benefícios, confiança em TI, fadiga de projetos) → **Operações** com menor prontidão.
- **Ambiente de dados:** inventário: Core Banking (CBS), CRM, DataMart Comercial; **lacunas:** dicionários dispersos, linhagem não documentada, duplicação de “NIF Cliente”.

**Entregáveis:**
- **Mapa de sistemas e flux**
