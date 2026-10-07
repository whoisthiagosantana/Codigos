# Protocolo Sítio Seguro — Cenário hipotético: peste pneumônica (início de 2027)

> **Natureza deste material.** Exercício de planejamento de contingência para um cenário **hipotético**.
> Não é previsão, não é alerta oficial e **não substitui orientação médica ou das autoridades de saúde**.
> Tudo que está aqui é de baixo custo, reversível e útil mesmo que o cenário nunca aconteça
> (estoques são consumidos e rotacionados; nada é "perdido").

## O cenário em uma frase

Surto de **peste pneumônica** (*Yersinia pestis*) com origem na Rússia no início de 2027, dissemina-se
por viagens internacionais. A família mora em **sítio pequeno, longe dos grandes centros** (premissa: Brasil),
quer se preparar **em degraus** e prever a chegada de **familiares de fora**, que podem trazer a doença.

## Correção importante de conceito

A peste **não é vírus: é bactéria**. Isso é uma **boa notícia**:

| | Peste do século XIV (Peste Negra) | Século XXI |
|---|---|---|
| Tratamento | Nenhum | **Antibióticos eficazes** (estreptomicina, gentamicina, doxiciclina, ciprofloxacino/levofloxacino) |
| Condição do paciente | Morte em 2–3 dias, quase sempre | Alta chance de sobrevivência **se tratada nas primeiras ~24 h** dos sintomas |
| Prevenção de contatos | Inexistente | **Profilaxia pós-exposição** com antibiótico por ~7 dias |
| Compreensão | "Miasma" | Conhecemos o agente, os vetores e a transmissão |

O risco real é **sistêmico**: hospitais lotados, falta de antibiótico, transporte e abastecimento interrompidos.
Por isso o plano mistura **saúde + logística + convivência**.

## Como navegar

```
protocolo-peste-2027/
├── README.md                      ← você está aqui
├── 00-cenario-e-premissas.md      ← o que é a doença, como se transmite, premissas do plano
├── 01-niveis-e-gatilhos.md        ← NÍVEIS 0–5: o que dispara a escalada (calendário + eventos)
├── fases/
│   ├── fase-0-nov-dez-2026.md     ← construir a base (calma, barato, sem alarde)
│   ├── fase-1-1T-2027.md          ← vigilância ativa; completar estoques
│   ├── fase-2-2T-2027.md          ← pré-chegada ao país; protocolos de visita ativados
│   ├── fase-3-3T-2027.md          ← cenário crítico; "porteira fechada" condicional
│   └── fase-4-4T-2027.md          ← sustentação, saída gradual e balanço
├── protocolos/
│   ├── A-recepcao-de-familiares.md      ← como receber quem vem de fora (quarentena de chegada)
│   ├── B-isolamento-e-cuidado-do-doente.md ← quarentena/isolamento em casa e cuidado de caso suspeito
│   ├── C-higiene-e-descontaminacao.md   ← máscaras, EPI, limpeza, lavanderia, descarte
│   ├── D-roedores-pulgas-animais.md     ← vetores: o lado "bubônico" que o sítio precisa dominar
│   ├── E-saude-e-farmacia.md            ← kit de saúde, o que conversar com o médico
│   ├── F-agua-comida-energia.md         ← autonomia logística
│   ├── G-novos-moradores-e-convivencia.md ← parentes que vão morar no sítio: regras, capacidade, saúde mental
│   └── H-comunicacao-e-fontes.md        ← de onde tirar informação confiável, contatos, comunidade
└── fichas/
    ├── lista-mestra-de-itens.md         ← checklist de compras por fase e por prioridade
    ├── ficha-triagem-visitante.md       ← imprimir: pergunta-e-registro de chegada
    └── registro-diario-sintomas.md      ← imprimir: temperatura e sintomas na quarentena
```

## Como usar (resumo de 5 linhas)

1. Leia `00` e `01` (15 min). Defina quantas pessoas moram e quantas podem vir (`G`).
2. Execute a **Fase 0** (nov–dez/2026) — é a mais importante e a mais barata.
3. A cada mês, consulte as fontes de `H` e confira o **nível** em `01`. **O nível manda, não o calendário.**
4. Imprima as `fichas/` e deixe-as na pasta do sítio, junto com este protocolo.
5. Treine a família uma vez (simulado de 30 min de chegada de visitante — `A`).

## Premissas (ajuste ao seu caso)

- Família-base de **4 pessoas** (2 adultos + 2 crianças/idosos). Quantidades por pessoa estão indicadas.
- Sítio pequeno, **poço/nascente + energia da rede**, 1 casa principal e, se possível, 1 espaço separado
  (edícula, casa de caseiro, galpão adaptável, cômodo com entrada independente).
- Distância ao hospital/UPA/pronto-socorro: **40 min a 2 h** de carro.
- Localização no Brasil. Se houver **foco natural de peste** na sua região (Nordeste: CE, PE, PB, BA; norte de MG;
  Serra dos Órgãos/RJ), o cuidado com roedores e pulgas (`D`) passa a ser prioridade **já na Fase 0**.

## Autoria e revisão

Elaborado como material de planejamento. **Revise com um médico de confiança** (clínico/infectologista)
os itens de `E` antes de comprar qualquer medicamento, e com a Vigilância Epidemiológica do seu município
as orientações locais.
