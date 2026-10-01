# Família Extrajudicial OS

`familia-extrajudicial-os` · versão 0.1.0 · Luis Sbroggio.

Estrutura inicial de um plugin para o **advogado dos interessados**, voltado à preparação de divórcio, união estável e inventário extrajudiciais. A entrega planejada abrange dossiê documental, requerimento, minuta de proposta para revisão humana e orientação pós-escritura.

## Estado desta entrega

A lane B0 cria os manifestos, a licença, o hook e a cópia do corpus local. Skills e comandos serão implementados pelas lanes de conteúdo; o B0 não cria nenhum desses componentes. O rol planejado tem 32 skills e 14 comandos, incluindo as futuras portas `/familia-extrajudicial-install` e `/familia-extrajudicial-master`. Esta estrutura não demonstra execução dessas portas, revisão jurídica integral ou prontidão para distribuição.

## Recorte e limites

- Divórcio consensual; declaração/reconhecimento, convenção patrimonial e dissolução consensual de união estável. Termo, alteração, certificação e conversão registrais entram somente como orientação de vias.
- Inventário e partilha, com incidentes delimitados: sobrepartilha, negativo, adjudicação, renúncia, cessão e alienação para despesas, sujeitos às condições próprias.
- Menor/incapaz: preparação especializada somente após prova das condições, representação e manifestação favorável do MP. Testamento: autorização judicial expressa transitada e demais condições verificadas, com exame prévio do conteúdo impeditivo.
- Base federal com lacunas estaduais explícitas. Não presumir alíquota, prazo, isenção, tabela de emolumentos ou prática administrativa de qualquer UF.
- Qualificação, lavratura, registro, manifestação do MP, decisão judicial e homologação fiscal cabem aos responsáveis externos. O plugin prepara documentos pelo lado dos interessados; não emite escritura lavrada nem cria comprovantes de eventos externos.
- Casos litigiosos, peças judiciais e planejamento autônomo ficam fora do recorte. Documentos de clientes permanecem em pasta privada, separados por cliente e matéria, fora do source.

## Tensões preservadas — 🔴

As restrições abaixo são orientação de produto; o hook não as executa. A implementação e a revisão independente das lanes seguintes devem demonstrar os bloqueios.

| Tensão | Âncora no corpus local | Limite |
| --- | --- | --- |
| Inventário com incapaz/testamento | `context/cpc-familia-extrajudicial.md`, art. 610; `context/cc-familia-sucessoes.md`, art. 2.016; `context/res-cnj-35-compilada.md`, arts. 12-A e 12-B, III–IV | Não declarar cabimento incontroverso; manter análise humana registrada. Sem provas obrigatórias ou conciliação comprovada da combinação incapaz+testamento, bloquear proposta especializada. |
| Filhos incapazes no divórcio | `context/cpc-familia-extrajudicial.md`, art. 733; `context/res-cnj-35-compilada.md`, art. 34, §§2º–3º | Exigir prova da resolução judicial prévia e análise humana explícita da tensão. |
| Nascituro na dissolução de união estável | `context/cpc-familia-extrajudicial.md`, art. 733; `context/cnn-familia-centrais-eletronico.md`, art. 537, §6º; `context/res-cnj-35-compilada.md`, arts. 34, §1º, e 46-A | Bloqueio de produto preservado; não autorizar automaticamente nem transportar a regra para divórcio ou nascituro do espólio. |
| Declaração negativa versus inventário com testamento | `context/res-cnj-35-compilada.md`, arts. 21 e 12-B | Não exigir declaração falsa; adaptação depende de qualificação humana. |
| Consulta RCTO fora do inventário | `context/cnn-familia-centrais-eletronico.md`, art. 441, II; `context/prov-cnj-56-rcto.md`, arts. 1º–2º | Não generalizar a obrigatoriedade para divórcio sem sucessão. |

Permanecem pendentes a atualização exaustiva, decisões suspensivas pertinentes, regras estaduais, prática administrativa e operação real do e-Notariado. Jurisprudência sem inteiro teor oficial conferido não sustenta afirmação dependente dela. A presença do Código de Ética e do art. 2.016 no corpus atual não equivale a aprovação jurídica dos seus usos.

## Estrutura

```text
.claude-plugin/plugin.json
.claude-plugin/marketplace.json
hooks/hooks.json
context/                       # cópia integral do context-draft, nomes preservados
skills/.gitkeep
commands/.gitkeep
LICENCA
README.md
```

O marketplace local aponta para `./`, onde está o plugin. Não há URL de repositório publicada nesta entrega. O único hook é `SessionStart`, no formato wrapped com chave `hooks`, e executa somente `echo`, sem Python ou dependência externa.

## Corpus e revisão

Os arquivos em `context/` preservam os textos, índices, marcadores e notas do draft. Sua cópia não certifica fidelidade, vigência, abrangência integral ou solução das tensões. Cada fundamento futuro deve ser conferido no texto literal, com versão e limites registrados; não preencher artigos ausentes por memória.

Cada futuro `SKILL.md` deve ter **até 11.004 bytes UTF-8**, medidos com `wc -c`, e ser o único arquivo de sua pasta. Guard anti-alucinação, validador normativo e revisão R1→R4 são responsabilidades distintas a implementar e verificar nos caminhos de execução, inclusive comandos diretos.

Suporte: **luis@sbroggio.io**. Uso sujeito à [LICENCA](LICENCA).
