---
description: "Seleciona e prepara incidentes sucessórios extrajudiciais com provas, limites e revisão humana obrigatória."
argument-hint: "[sobrepartilha | negativo | adjudicação | renúncia | cessão | despesas]"
---

# Incidentes da família extrajudicial

Receba o pedido em $ARGUMENTS e confirme a operação e os fatos faltantes antes de produzir proposta. Atue pelo advogado dos interessados; lavratura, qualificação e decisões de órgãos externos permanecem com seus responsáveis.

1. Identifique interessado assistido, consenso/divergências, UF(s), óbito/datas do negócio, modalidade, capacidade, nascituro, testamento, regime patrimonial e documentos. Use somente anexos normativos locais com trecho comprovado. Dados do caso ficam exclusivamente na pasta privada indicada pelo operador, separados por cliente/matéria.
2. Execute `anti-alucinacao-familia-extrajudicial` e `validador-familia-extrajudicial` antes da preparação. Não invente anuência, assinatura, manifestação MP, trânsito, guia, orçamento, pagamento, escritura ou registro. Fonte ausente ou atualização não conferida gera pendência; não buscar jurisprudência por notícia nem preencher regra da UF por analogia.
3. Selecione pelo objeto real:

| Pedido | Skill | Entrada decisiva |
|---|---|---|
| Sobrepartilha, inventário negativo ou adjudicação | `sobrepartilha-negativo-e-adjudicacao` | inventário anterior/bens novos, ausência de acervo documentada ou herdeiro único com totalidade |
| Renúncia | `renuncia-hereditaria-na-via-extrajudicial` | aceitação anterior, vontade, título, cônjuge e destinatário |
| Cessão do direito/quinhão | `cessao-hereditaria-na-via-extrajudicial` | cedente/coerdeiros/cessionário, objeto, preço, títulos e preferência |
| Alienação pelo inventariante para despesas | `alienacao-do-espolio-para-despesas` | nomeação, seis requisitos de R35 11-A, guias, orçamentos, garantia e preço vinculado |

Não confunda cessão por herdeiro com venda pelo inventariante, renúncia dirigida com pura, nem negativo com isenção fiscal. Se o pedido misturar operações, separe requisitos e dependências; uma skill não valida automaticamente a seguinte.

4. Preserve os bloqueios: renúncia parcial/condicionada/a termo (CC 1.808) e irrevogabilidade (1.812); ineficácias de CC 1.793, §§2º–3º, e preferência (1.794) e 180 dias após a transmissão (1.795); vedação de disposição dos direitos do incapaz (R35 12-A, §1º), inclusive sob 11-A. Sem todos os seis requisitos do 11-A, não preparar proposta de apresentação; prazo de despesas até um ano desde a venda não é prazo fiscal universal.
5. Menor/incapaz exige provas de partes ideais em cada bem, representação e MP favorável antes da proposta; nascituro do espólio exige aguardar nascimento/parentalidade ou prova de não nascimento com vida. Testamento vai a `inventario-com-testamento`, com autorização expressa transitada e demais condições de R35 12-B. Declaração irrevogável/reconhecimento de filho impede escritura; não produzir negativa falsa. Incapaz com testamento bloqueia proposta sem conciliação oficial específica comprovada. Preserve tensões 🔴 CPC 610/CC 2.016 × R35 12-A/12-B e R35 21 × 12-B. Impugnação, divergência/litígio e bens no exterior recebem diagnóstico/encaminhamento, sem peça judicial ou promessa de escritura.
6. Entregue matriz `requisito → prova → arquivo/trecho → responsável → situação`, variante, fatos confirmados, fontes/versão/captura/data de corte, selos e limites federais/locais, documentos faltantes, próxima providência e impedimento. Use `PREPARAÇÃO CONDICIONADA À REVISÃO HUMANA`, `PENDENTE DE PROVA`, `BLOQUEADO` ou `FORA DO RECORTE`. Lacuna impeditiva exclui minuta de apresentação; não rotular como apto à lavratura.
7. Ao final, execute `anti-alucinacao-familia-extrajudicial` → `validador-familia-extrajudicial` → `suprema-corte-familia-extrajudicial`, R1→R4 default-on (fatos; fundamentos; documentos/UF/condições; postura/sigilo). Corrija/retire texto reprovado. Dependência ausente impede entregar proposta como revisada; registre a pendência. Comando direto não salta os gates da skill.

Âncoras a ler: `context/res-cnj-35-compilada.md`, arts. 11, §2º/11-A/12-A/12-B/15–17/21/25–29; `context/cc-familia-sucessoes.md`, arts. 1.793–1.795/1.806/1.808–1.813/2.016; `context/cpc-familia-extrajudicial.md`, art. 610; `context/lc-227-2026-itcmd.md`, arts. 147/150, I/151/182, III. Referências delimitam conferência, não aprovação automática. Controles por instrução (guidance only), sem enforcement por hook. Suporte: suporte@iapx.pro.
