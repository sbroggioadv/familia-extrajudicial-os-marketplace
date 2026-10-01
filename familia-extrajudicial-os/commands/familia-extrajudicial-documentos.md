---
description: Organiza dossiê documental e representação por ato familiar extrajudicial.
argument-hint: "ato, UF(s), modalidade, datas e documentos disponíveis"
---

# /familia-extrajudicial-documentos

Receber o pedido em `$ARGUMENTS` e os documentos efetivamente fornecidos. Identificar operação, interessado assistido, consenso/divergências, capacidade, filhos/nascituro, testamento, UF(s), datas e modalidade; solicitar apenas dados necessários que faltarem. Guardar documentos exclusivamente na pasta privada escolhida, separados por cliente/matéria, nunca no source.

Ler e aplicar `triagem-familia-extrajudicial`, `anti-alucinacao-familia-extrajudicial` e `validador-familia-extrajudicial`, conferindo as fontes literais apontadas pelas skills. Falta de controle, documento ou fundamento vira pendência, sem presumir gate executado. Atalho direto percorre os mesmos controles do master.

Executar `dossie-documental-familiar` e depois `assistencia-e-representacao-familiar`. Acionar `lacunas-estaduais-do-procedimento` quando houver validade, documento adicional, tributo ou forma local ainda não comprovados. Entregar índice/checklist por ato e quadro de assinaturas/representação, com origem, fundamento, arquivo/trecho, faltantes, responsável e etapa impedida.

R35 12-A, caput: parte ideal em cada um dos bens e manifestação favorável do MP. Sem prova de qualquer condição, limitar a coleta/pendências, sem proposta especializada.

Separadamente, conferir prova da representação legal do incapaz (B2); o mandato do interessado capaz segue R35 12. Sem prova da representação aplicável, manter coleta/pendências, sem proposta especializada. Testamento exige certidão, conteúdo e autorização judicial expressa transitada nos termos de R35 12-B. Declarar 🔴 CPC 610/CC 2.016 × R35 12-A/12-B, III–IV, e CPC 733 × R35 34, com análise humana registrada quando incidentes. Nascituro na dissolução bloqueia preparação; não ocultar gravidez nem exigir negativa falsa de testamento. Não universalizar validade de certidões, prazo de mandato ou rito da UF. Não completar fonte estadual por analogia.

Finalizar obrigatoriamente com `suprema-corte-familia-extrajudicial`, R1→R4 default-on (fatos/provas/ator; fundamentos/vigência/tensões; documentos/UF/condições; sigilo/postura/encaminhamento), registrando achados. Emitir estado `PREPARAÇÃO CONDICIONADA À REVISÃO HUMANA`, `PENDENTE DE PROVA`, `BLOQUEADO` ou `FORA DO RECORTE`, com motivo, fonte/data de corte, documentos recebidos/faltantes, quadro requisito → prova → arquivo/trecho → responsável → situação e próxima providência/impedimento. Não anunciar aprovação da escritura ou aptidão à lavratura. Estes gates são instruções ao agente (guidance only), não execução automática por hook.

Suporte: luis@sbroggio.io.
