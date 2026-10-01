# ÍNDICE-C — anexos P0 verbatim · CX-C · familia-extrajudicial (30/09/2026)

Fontes exclusivamente oficiais (planalto.gov.br, legis.senado.leg.br). Nenhum agregador. Nada commitado. Escrita só em `context-draft/`. `html2text` ausente; HTML → texto por `html.parser` (stdlib), `<strike>`/`<s>`/`<del>`/`line-through` → `~~texto~~`. User-Agent `Mozilla/5.0`. Data da captura: 30/09/2026.

Contagem de artigos **por comando** (cwd = esta pasta). Recorte literal não é diploma integral.

| Anexo | Arquivo | URL oficial | HTTP | Nº de artigos (comando) | Pendências |
|---|---|---|---|---|---|
| LC 227/2026 Livro II + alterador CTN + 182 + DOU | `lc-227-2026-itcmd.md` | https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp227.htm | **200** (1.334.008 B) | **22** artigos da LC: Livro II 146–164 = **19** (`python3 -c "import re; t=open('lc-227-2026-itcmd.md').read().split('\`\`\`')[1]; print(len(set(int(x) for x in re.findall(r'Art\\.\\s+(\\d+)', t))))"`) + 165 + 181 + 182 (`grep -cE '^## Art\. (165\|181\|182)'` = 3). `grep -cE '^\s*Art\.'` = **24** (inclui CTN 35/35-A/38 citados no art. 165) | Cláusula de efeitos = art. 182 (publicação / 1º/01/2027 / eleição CGIBS). Sanção na fonte: «Brasília, 13 de janeiro de 2026». Rodapé Planalto: DOU 14.1.2026, republicado 15.1.2026, retificado 23.1.2026. Páginas in.gov.br do DOU não reabertas (rodapé já traz as três datas). |
| CF art. 155 | `cf-itcmd.md` | https://www.planalto.gov.br/ccivil_03/constituicao/constituicao.htm | **200** (1.839.482 B) | **1** artigo (155), com redações sucessivas na mesma página. `grep -cE 'Art\. 155'` = **3** (título `## Art. 155` + texto original + redação EC 3/1993) | Fonte sem `<strike>` neste trecho; original e emendas (EC 3/1993, 33/2001, 42/2003, 87/2015, 126/2022, 132/2023, 137/2025) copiados como a página exibe. |
| CTN 35–42 (revogados preservados) | `ctn-itbi-contraste.md` | https://www.planalto.gov.br/ccivil_03/leis/l5172.htm | **200** (430.346 B) | **11** marcadores `python3 -c "import re; print(len(re.findall(r'Art\\.\\s*\\n?\\s*(?:35-A\|3[5-9]\|4[0-2])\\b', open('ctn-itbi-contraste.md').read())))"` — números 35, 35-A, 36, 37, 38, 39, 40, 41, 42 (35 e 41 com duas redações) | Compilado `l5172compilado.htm` HTTP **200** (289.910 B) lido: parágrafo único do art. 35 e art. 39 só como «(Revogado)», sem texto anterior. Captura usou `l5172.htm`, que traz o texto antigo em `~~tachado~~`. |
| Res. Senado nº 9/1992 (teto) | `res-senado-9-1992.md` | https://legis.senado.leg.br/norma/590017/publicacao/15785996 | **200** (43.191 B) | **4** — `grep -cE '^\s*Art\. '` (arts. 1º–4º, integral) | `legis.senado.leg.br/norma/562654` HTTP 200 = casca sem o ato (descartado). Fecho publicado: «Senado Federal, 5 de maio de 1991»; título «RESOLUÇÃO Nº 9, DE 1992». Ementa: «inciso l» como na fonte. |
| Lei 10.169/2000 emolumentos | `lei-10169-emolumentos.md` | https://www.planalto.gov.br/ccivil_03/leis/l10169.htm | **200** (19.650 B) | **10** — `grep -cE '^\s*Art\. '` (arts. 1º–10, integral) | Tabelas estaduais de emolumentos fora da base federal. Parágrafo único original do art. 2º em `~~tachado~~`; §§ 1º–2º Lei 13.986/2020. |
| Lei 15.040/2024 seguro | `lei-15040-seguro.md` | https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2024/lei/l15040.htm | **200** (165.051 B) | **134** — `grep -cE '^\s*Art\. '` (arts. 1º–134, integral) | Art. 116 (capital por morte não é herança) + 133 (revogações CC/DL 73) + 134 (vacatio: 1 ano da publicação oficial). Rodapé: DOU 10.12.2024. Data civil de início de vigência não calculada aqui. |
| Estatuto da OAB (Lei 8.906/1994) | `estatuto-oab.md` | https://www.planalto.gov.br/ccivil_03/leis/l8906.htm | **200** (195.140 B) | **3** núcleos — `grep -cE '^## Art\.'` (2º+2º-A; 7º+7º-B; 34). Recorte, não o diploma inteiro. | Código de Ética da OAB **não capturado** (fora da lista desta tarefa; manifesto pedia captura oficial em oab.org.br — permanece 🟡). Inciso II original do art. 7º em `~~tachado~~`. |
| LGPD vigente (dados sensíveis / processo) | `lgpd.md` | https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm | **200** (230.913 B) | **4** — `grep -cE '^## Art\.'` (5º, 6º, 7º, 11). Recorte. | Página não compilada `l13709.htm` HTTP **200** (310.252 B) também baixada. Compilado traz art. 5º, VIII e XIX na redação da Lei 15.352/2026. A fonte não contém a palavra «advogado»; bases de processo: art. 7º, VI e art. 11, II, d. |

## Tentativas oficiais descartadas

| URL | HTTP | Motivo |
|---|---|---|
| https://legis.senado.leg.br/norma/562654 | 200 | Portal sem o texto da Resolução 9/1992 |
| normas.leg.br (URN) | 200 | SPA sem corpo normativo |
| pesquisa.in.gov.br (uma query de republicação LC 227) | 500 | Rodapé do Planalto já traz DOU 14.1 / 15.1 / 23.1 |

## Cautelas de extração (manifesto)

- LC 227: produção de efeitos no **art. 182** + rodapé DOU 14.1.2026 / republicação 15.1.2026 / retificação 23.1.2026. A data de sanção na fonte é 13 de janeiro de 2026.
- CTN: revogados do art. 35 (parágrafo único) e do art. 39 preservados em `~~ ~~` a partir de `l5172.htm`.
- Nenhum arquivo chama CC 1.829 de «herdeiros necessários» (dispositivo fora deste lote).
- Código de Ética: CX-C não capturou (nenhum artigo inventado). **CX-D fechou** com `codigo-etica-oab.md` (Resolução CFOAB 02/2015 vigente — ver tabela abaixo).

## Arquivos desta tarefa (CX-C)

`lc-227-2026-itcmd.md` · `cf-itcmd.md` · `ctn-itbi-contraste.md` · `res-senado-9-1992.md` · `lei-10169-emolumentos.md` · `lei-15040-seguro.md` · `estatuto-oab.md` · `lgpd.md` · `INDICE-C.md` · `DONE-CX-C`

---

# CX-D — lastro RDS1 G1/G2 · 30/09/2026

Fontes exclusivamente oficiais (planalto.gov.br, oab.org.br / CFOAB). Nenhum agregador. Nada commitado. Escrita só em `context-draft/`. User-Agent `Mozilla/5.0`. Data da captura: 30/09/2026.

| Anexo | Arquivo | URL oficial | HTTP | Nº de artigos (comando) | Pendências |
|---|---|---|---|---|---|
| CC arts. 2.016 e 2.017 (acréscimo ao final; RDS1 G1) | `cc-familia-sucessoes.md` (bloco CX-D após a Contagem) | https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm | **200** (923899 B) | **2** — `grep -cE '^\s*Art\. 2\.01[67]' cc-familia-sucessoes.md` no bloco CX-D = 2 (2.016 e 2.017). Cabeçalho CX-B e tabela Contagem **intocados** (continuam 50) | 2.017 veio junto na fonte, imediatamente após 2.016; recorte pára antes de 2.018. Mesma página compilada da captura CX-B. |
| Código de Ética e Disciplina da OAB vigente (RDS1 G2) | `codigo-etica-oab.md` | https://www.oab.org.br/publicacoes/AbrirPDF?LivroId=0000004085 (menu em https://www.oab.org.br/leisnormas/legislacao → «Código de Ética e Disciplina (CED)») | **200** (241272 B, PDF 24 p.) | **22** — `grep -cE '^\s*Art\. ' codigo-etica-oab.md` = 22 (Cap. III arts. 9º–26 = 18; Cap. VII arts. 35–38 = 4) | Capítulos identificados pelo sumário **do próprio PDF** (Título I): III «DAS RELAÇÕES COM O CLIENTE» e VII «DO SIGILO PROFISSIONAL». Resolução n. 02/2015 (DOU 04.11.2015). Nota 1 do PDF: vigor 1º/09/2016 (Res. 03/2016). Recorte, não o diploma inteiro. |

## Tentativas oficiais descartadas (CX-D / OAB)

| URL | HTTP | Motivo |
|---|---|---|
| https://www.oab.org.br/visualizador/19/codigo-de-etica-e-disciplina → `/Content/pdf/LegislacaoOab/codigodeeticarevnv.pdf` | 200 (177442 B) | Menu rotula «CED (anterior - revogado pelo novo Código)». PDF abre «(Revogado pela Resolução n. 02/2015)». **Não vigente.** |
| https://www.oab.org.br/Content/pdf/LegislacaoOab/codigodeetica.pdf (e `CodigoDeEtica.pdf`) | 200 (122932 B) | CED de 1995 (CreationDate 2010). **Não vigente.** |
| https://eticaedisciplina.oab.org.br/ | 200 | SPA Angular (`<app-root>`), sem diploma no HTML |
| https://www.cfoab.org.br/ | 000 / falha | Host sem resposta útil nesta captura |
| Vários paths `/Content/pdf/LegislacaoOab/resolucao022015.pdf`, `ced2015.pdf`, `novocodigodeetica.pdf`, `/leisnormas` sem sufixo, `/noticia/codigo-de-etica-e-disciplina` | 404 / 500 | Filename guess; o vigente está em `AbrirPDF?LivroId=0000004085` |

## Arquivos desta tarefa (CX-D)

`cc-familia-sucessoes.md` (acréscimo ao final) · `codigo-etica-oab.md` · `INDICE-C.md` · `DONE-CX-D`

---

# FCX-C — correção RCX-AC GRAVE 1 e 2 · 30/09/2026

Revisão: `.aiox/orca/reports/2026-09-30-RCX-AC.md` §4. Só estes arquivos: `lc-227-2026-itcmd.md`, `lei-10169-emolumentos.md`, `estatuto-oab.md`, `ctn-itbi-contraste.md`. Nada commitado. NUNCA push.

## G1 — C1 (U+0080–U+009F) · antes / depois

Causa: bytes cp1252 (`0x93` `0x94` `0x96`) decodificados como iso-8859-1 → controles invisíveis. Mapa aplicado, conferido contra a fonte Planalto re-baixada (HTTP 200, cp1252): `U+0093`→`“` (U+201C) · `U+0094`→`”` (U+201D) · `U+0096`→`–` (U+2013). Cabeçalho dos 3 anexos: «Encoding iso-8859-1…» → «Encoding cp1252…».

| Arquivo | C1 antes | C1 depois | Glifos |
|---|---:|---:|---|
| `lc-227-2026-itcmd.md` | **54** (27× U+0093, 27× U+0094) | **0** | `“`/`”` presentes na fonte (250/251) |
| `lei-10169-emolumentos.md` | **2** (1× U+0093, 1× U+0094) | **0** | `alínea “b”` = 1/1 na fonte |
| `estatuto-oab.md` | **1** (1× U+0096) | **0** | `II – a inviolabilidade` = 1/1 na fonte |
| **Total** | **57** | **0** | |

Prova (cwd = esta pasta):

```sh
python3 -c "
from pathlib import Path
files=['lc-227-2026-itcmd.md','lei-10169-emolumentos.md','estatuto-oab.md']
for f in files:
    n=sum(1 for ch in Path(f).read_text(encoding='utf-8') if 0x80<=ord(ch)<=0x9F)
    print(f, n)
"
# lc-227-2026-itcmd.md 0
# lei-10169-emolumentos.md 0
# estatuto-oab.md 0
```

## G2 — tachado CTN art. 35 · antes / depois

Fonte `l5172.htm` HTTP 200: cada parágrafo revogado em `<strike>` próprio (Seção III, título, caput art. 35, I, II, III, parágrafo único). O anexo tinha **fechamento `~~` sem abertura** no fim do parágrafo único — caput+incisos+parágrafo único **não renderizavam tachados**.

| | `~~` no arquivo | Art. 35 revogado |
|---|---|---|
| **Antes** | 9 (ímpar; 1 órfão + pares dos arts. 39 e 41 + 2 do cabeçalho «~~texto~~») | caput/I–III/parágrafo único **sem** abertura; só `~~` no fim |
| **Depois** | **10** (par) | bloco `~~Art. 35. … herdeiros ou legatários.~~` — inclui caput, incisos I–III e parágrafo único *causa mortis*; nota «(Revogado pela Lei Complementar nº 227, de 2026)» **fora** do tachado, como na fonte |

Arts. 39 e 41 já estavam com par `~~…~~` — intocados. Cabeçalhos tachados da antiga Seção III (achado MENOR M3 da RCX-AC) **não** foram acrescentados nesta correção.

## Arquivos desta tarefa (FCX-C)

`lc-227-2026-itcmd.md` · `lei-10169-emolumentos.md` · `estatuto-oab.md` · `ctn-itbi-contraste.md` · `INDICE-C.md` · `DONE-FCX-C`
