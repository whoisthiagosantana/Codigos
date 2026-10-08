# 03 — Reconciliação de visões: este protocolo × plano do agente externo

Dois planos independentes foram escritos para o mesmo cenário. Este arquivo registra **o que cada um trouxe,
onde divergiram e o que foi decidido**. O original do outro agente está em
`contribuicoes/agente-externo-plano-resiliencia/`.

## 1. Em uma frase cada

- **Este protocolo (v1):** *operacional e detalhado.* Níveis 0–5 por gatilho, tarefas mês a mês, fichas, orçamento, convivência de novos moradores.
- **Plano externo:** *epistêmico e cauteloso.* Insiste em separar **fato, hipótese e regra doméstica**, em não confinar por rumor, em preservar o acesso do doente à assistência e em adaptar tudo se o agente mudar.

A visão do externo tornou-se uma **camada de rigor** sobre a operação do v1. Os dois se complementam.

## 2. Mapa de fases (os dois usam janelas equivalentes)

| Janela | Plano externo | Este protocolo (níveis / fases) |
|---|---|---|
| Nov–dez/2026 | Fase 1 — Preparação | Nível 0 / Fase 0 |
| Jan–mar/2027 | Fase 2 — Vigilância | Nível 1→2 / Fase 1 |
| Abr–jun/2027 | Fase 3 — Restrição | Nível 2→3 / Fase 2 |
| Jul–set/2027 | Fase 4 — Contenção | Nível 3→4 / Fase 3 |
| Out–dez/2027 | Fase 5 — Crise | Nível 4→5 / Fase 4 |

Os **gatilhos** de ambos coincidem na lógica ("só sobe com evidência verificável") e foram mantidos na tabela do `01`.

## 3. O que foi incorporado do plano externo

| Contribuição | Onde entrou |
|---|---|
| **Situação real em out/2026** (Irkutsk; causa não confirmada; sem casos confirmados de peste) | `00-cenario-e-premissas.md` §0 |
| Rótulos de **nível de confiança** (alta / dependente de contexto / hipótese) e reavaliação se o agente for outro | `02-fontes-e-limites.md` |
| **"Nunca manter medidas só porque o calendário avançou"**, critérios de redução de alerta | `01-niveis-e-gatilhos.md` |
| Prazo de quarentena como **regra administrativa doméstica**, não prazo médico; incubação usual 1–3 d | `01`, `00`, `protocolos/A` |
| Metas escalonadas **72 h → 14 d → 30 d** de estoque | `protocolos/F`, `fases/fase-0` |
| Água de emergência **não cobre banho, horta ou animais** (dimensionar à parte) | `protocolos/F` |
| **Oxímetro é apoio, não critério isolado** | `protocolos/B`, `E`, `fichas/registro-diario-sintomas` |
| **Não estocar nem usar antibiótico por conta própria**; nada de medicação veterinária | `protocolos/E`, `B` |
| **48 h de antibiótico ≠ tratar em casa 48 h** | `protocolos/B` §8 |
| **Não é necessário pulverizar compras ou pessoas**; fômites têm papel pequeno na peste pneumônica | `protocolos/C`, `A` |
| Máscara: **sem prazo universal de reuso**; crianças < 2 anos **sem máscara** | `protocolos/C` |
| **Barraca não substitui estrutura segura**, sobretudo para crianças e doentes | `protocolos/G` §10 |
| **Governança**: 5 papéis, rotina semanal/quinzenal/mensal/trimestral, tabela de decisões | `protocolos/I-governanca-e-rotinas.md` (novo) |
| **Zoneamento A–E** e fluxo de pessoas | `protocolos/J-zoneamento-e-fluxo.md` (novo) |
| **Alertas contra excessos**: privacidade do visitante, não impedir doente de ter assistência | `protocolos/I`, `A` |
| Checklists: auditoria inicial, pré-chegada, revisão trimestral | `fichas/checklists-auditoria-e-pre-chegada.md` (novo) |

## 4. Divergências e decisão tomada

| Tema | v1 (antes) | Plano externo | Decisão |
|---|---|---|---|
| **Incubação da forma pneumônica** | "1–4 d, pode chegar a ~6 d" | "1–3 d usual" | Adotado **"usualmente 1–3 dias (algumas fontes, até ~4)"**. O "~6 d" do v1 foi escrito de memória e **retirado**. |
| **Duração da quarentena** | 7 d (N2), 10 d (N3), 14 d (N4) | "até 7 d, regra administrativa" | **7 dias é a regra-base**. 10–14 d ficam como **opção ultraconservadora da família** (ex.: casa com idoso/imunossuprimido), rotulada como tal, sem base médica. |
| **Quarentena de objetos / desinfetar compras** | Sugerido (24–72 h, álcool nas embalagens) | "Não é necessário" | **Reclassificado como opcional/baixa prioridade**; lavar as mãos importa mais que desinfetar embalagens. |
| **Kit de antibióticos** | Conversar com o médico sobre kit de emergência | "Não estocar" | **Alinhado: só com prescrição individual e gatilho de uso combinado com o médico**; nunca por conta própria. O v1 já dizia isso, agora com ênfase. |
| **Água** | 4 L/pessoa/dia | 3,8 L (≈ 1 galão) | Equivalentes. Mantido 4 L; acrescentada a ressalva do externo (higiene/animais à parte). |
| **Metas de estoque na Fase 0** | 30 d de comida direto | Escalonado 72 h → 14 d → 30 d | **Escalonado adotado** como ordem de compra: o essencial primeiro, o resto conforme orçamento. |
| **Barraca como alojamento** | Citada como plano B | Rejeitada | **Removida** como alojamento de crianças/doentes. |
| **Papel de decisão** | 1 responsável + regra de 2 adultos | 5 responsáveis por área | **Combinados**: coordenador decide (com regra de 2 adultos) e há 4 responsáveis de área. |
| **Profundidade operacional** (fichas, orçamento, convivência) | Alta | Baixa | Mantido o do v1; o externo não cobria. |

## 5. Pontos em que o plano externo é **mais fraco** (e por quê o v1 prevaleceu)

- **Sem tratamento da chegada de familiares que vão *morar*:** é o pedido central do usuário; coberto por `protocolos/G`.
- **Sem orçamento, sem mês a mês, sem lista de itens com quantidades por nível.**
- **Pouca ênfase em vetores** (roedores/pulgas) além de menções; coberto por `protocolos/D`.
- **"Quarentena de até 7 dias"** sem distinguir o caso de contato exposto (que precisa de avaliação e profilaxia) — o v1 separa visitante assintomático (A) de contato exposto (B §6).

## 6. Pontos em que o plano externo é **mais forte** (e prevaleceu)

- Honestidade sobre o que é fato, hipótese e regra doméstica.
- Proporcionalidade (evitar confinamento sem evidência, evitar rituais sem benefício).
- Cuidado ético (privacidade, não negar assistência).
- Aviso de que **o plano é específico para o agente**: se for outro (p. ex. vírus respiratório de aerossol), tudo precisa ser reavaliado.
