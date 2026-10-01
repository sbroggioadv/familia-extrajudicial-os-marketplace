# ÍNDICE-B — Anexos CX-B · captura verbatim 30/09/2026

Captura da lane **CX-B** (manifesto: `../ACHADOS-CORPUS.md`, seção "Anexos `context/` necessários"). Fontes **exclusivamente oficiais** (`planalto.gov.br`). Nenhum agregador usado. Nada commitado, nada em push. Escrita restrita a `context-draft/`.

Os outros arquivos desta pasta — `cf-itcmd.md`, `cnn-familia-centrais-eletronico.md`, `ctn-itbi-contraste.md`, `estatuto-oab.md`, `lc-227-2026-itcmd.md`, `lei-10169-emolumentos.md`, `lei-15040-seguro.md`, `lgpd.md`, `prov-cnj-202-2025.md`, `prov-cnj-56-rcto.md`, `res-cnj-35-compilada.md`, `res-cnj-571-2024.md`, `res-cnj-695-2026.md`, `res-senado-9-1992.md`, `INDICE-A.md` e `INDICE-C.md` — **são de outras lanes**, não foram tocados nem verificados aqui. Verificação de autoria feita por marcador de cabeçalho próprio desta lane (`grep -c 'HTML baixado' *.md` → 1 só nos cinco anexos abaixo, 0 nos demais).

---

## Tabela de aceite — anexo → URL → HTTP → nº de artigos → pendências

Contagem de artigos **por comando**, executado nesta pasta:

```sh
grep -cE '^\s*(~~)?Art\. ' <arquivo>
```

| # | Anexo | URL oficial | HTTP | Nº de artigos capturados (comando) | Pendências |
|---|---|---|---|---|---|
| 1 | `cpc-familia-extrajudicial.md` | http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13105.htm | **200** (1.691.185 B) | **7** — arts. 610, 611, 617, 731, 732, 733, 1.046 | **Arts. 647 a 658 não capturados** (partilha judicial, destino da remissão do art. 731, § único): o manifesto os admite "só como fronteira, sem importar peças judiciais". **Art. 1.045** (vigência do CPC), imediatamente anterior ao 1.046, deliberadamente fora do recorte. Usada a página **não compilada** (`l13105.htm`), a mesma do corpus. Nenhum tachado dentro dos sete artigos. Vigência/DOU não conferidos além da página |
| 2 | `cc-familia-sucessoes.md` | https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm | **200** (923.899 B) | **50** — 104, 108, 215, 657, 661, 1.571, 1.581, 1.640, 1.641, 1.653, 1.657, **1.658–1.666**, 1.723–1.727, 1.793–1.795, 1.806–1.813, 1.829, **1.845–1.850**, **1.851–1.856**, 2.015 | Delimitação dos "e seguintes" resolvida pela estrutura da fonte e documentada no cabeçalho do anexo (comunhão parcial = Cap. III, 1.658–1.666, porque o 1.667 abre a comunhão universal; herdeiros necessários = Cap. II, 1.845–1.850; representação = Cap. III, 1.851–1.856, incluída porque o art. 1.856 trata do renunciante e o 1.811 remete à representação). **Marcadores "(Vide Recurso Extraordinário nº 646.721)" e "(Vide RE nº 878.694)" preservados como a fonte exibe, sem ler as decisões nem atribuir-lhes tese.** Nenhum tachado dentro dos 50 artigos. A Lei nº 15.040/2024 revoga CC 757–802 — **nenhum dos 50 artigos capturados está nessa faixa**; a revogação em si não foi verificada aqui (é do anexo `lei-15040-seguro.md`, outra lane). Alterações posteriores à data da página não verificadas em DOU |
| 3 | `lrp-familia-duvida.md` | https://www.planalto.gov.br/ccivil_03/leis/l6015compilada.htm | **200** (494.081 B) | **11** — 70-A, 94-A, 148, 198, 199, 200, 201, 202, 203, 204, 296 | **Remissões presentes nos blocos e NÃO capturadas** (fora do pedido do manifesto; declaradas, não incluídas em silêncio): **art. 188** — fixa o prazo dentro do qual o oficial indica a exigência, citado no caput do art. 198; **art. 1º, § 1º, I a III** — define quais registros o art. 296 alcança; **art. 149**; **art. 293** (nota de renumeração). O "art. 32" do art. 198, § 2º, é da Lei 8.935/1994 e está no anexo 4. Grafia da fonte preservada: arts. 199 a 204 como "Art. 199 -", com hífen (renumerados pela Lei 6.216/1975), não normalizada. **Cautela do manifesto registrada no cabeçalho:** este recorte não cria rito de dúvida aplicável ao tabelião de notas |
| 4 | `lei-8935.md` | https://www.planalto.gov.br/ccivil_03/leis/l8935.htm | **200** (68.570 B) | **4 artigos únicos** (30, 31, 32, 42-A) — o comando devolve **5** linhas porque o art. 42-A aparece **duas vezes** na fonte (versão tachada + versão vigente); ambas capturadas | **Art. 33** (gradação das penas do art. 32) **não capturado** — o bloco termina no fim do art. 32, conforme o recorte pedido. **Art. 42-A com duas versões na fonte:** a primeira marcada "(Incluído pela Lei nº 14.206, de 2021) (Revogado Pela Medida Provisória nº 1.085, de 2021)" em `~~tachado~~` e, em seguida, versão de idêntico teor reincluída — **as duas preservadas**, sem decidir qual vigora. **Tramitação da MP 1.085/2021 não rastreada.** No bloco 30–32 também vem tachada a redação anterior dos incisos XIV e XV do art. 30 (MP 1.085/2021) — preservada |
| 5 | `lei-11441-historica.md` | http://www.planalto.gov.br/ccivil_03/_ato2007-2010/2007/lei/l11441.htm | **200** (12.661 B) | **5** (arts. 1º a 5º, texto integral do diploma) — `grep -oE 'Art\. [0-9]' \| sort -u \| wc -l` devolve **9** porque o texto cita, dentro das próprias aspas da lei, quatro dispositivos do CPC/1973: **982, 983, 1.031 e 1.124-A** | **Texto histórico, não é rito vigente** — nota externa obrigatória no cabeçalho do anexo. A lei altera a **Lei 5.869/1973 (CPC/1973)**, substituída pela Lei 13.105/2015. O prazo "60 dias / 12 meses" do art. 983 citado no texto **não é o vigente**: no CPC/2015 o prazo está no **art. 611**, capturado no anexo 1. Cautela do manifesto respeitada: texto histórico não apagado e não apresentado como vigente. A página consultada não traz tachados |

**Total desta lane: 5 anexos, 77 artigos únicos capturados, 5 fontes oficiais, todas HTTP 200, zero agregador, zero bloqueio.**

---

## Verificação de fidelidade (não declarada — medida)

Cada parágrafo de ≥60 caracteres dentro dos blocos verbatim foi comparado com o texto bruto extraído da fonte, normalizando apenas espaços e os marcadores `~~`:

```sh
python3 - <<'PY'   # sq() = colapsar espaços + remover '~~'; testa sq(paragrafo) in sq(fonte)
```

| Anexo | Parágrafos ≥60 c testados | Presentes literalmente na fonte | Divergentes |
|---|---:|---:|---:|
| `cpc-familia-extrajudicial.md` | 26 | 26 | **0** |
| `cc-familia-sucessoes.md` | 127 | 127 | **0** |
| `lrp-familia-duvida.md` | 81 | 81 | **0** |
| `lei-8935.md` | 27 | 27 | **0** |
| `lei-11441-historica.md` | 26 | 26 | **0** |
| **Total** | **287** | **287** | **0** |

**287/287 = 100,00%.** Nenhuma palavra foi alterada, resumida ou reescrita. O teste é conservador: um parágrafo só passa se a cadeia inteira, caractere a caractere (após colapsar espaços), estiver na fonte.

Um defeito da primeira passada foi encontrado **por esta verificação e corrigido antes da entrega**: o fatiamento original não indexava artigos iniciados por `~~Art.` (versão tachada), e o bloco do art. 42-A da Lei 8.935 saiu com **apenas** a versão vigente — contradizendo a nota do próprio cabeçalho, que afirmava preservar as duas. Corrigido o índice de artigos para reconhecer `~~` e o fim do fatiamento para usar a **última** ocorrência do artigo final; regenerado e revalidado (42-A passou de 471 para 997 caracteres, com as duas versões e o marcador "(Revogado Pela Medida Provisória nº 1.085, de 2021)"). Duas notas de cabeçalho que exageravam o que havia sido capturado (arts. 33 e 1.045, e a presença de tachados em CPC/CC) também foram corrigidas para o estado real.

---

## Método de extração

- **`html2text` não está instalado nesta máquina** (`python3 -c "import html2text"` → módulo ausente; `which html2text` → vazio). O corpus original usou `html2text`; aqui a conversão foi feita com **`html.parser` da biblioteca padrão**, sem dependência externa.
- **Decodificação `cp1252`**: as páginas do Planalto não declaram `<meta charset>`; UTF-8 produzia *mojibake* (`homologao`). Todas as cinco fontes decodificaram corretamente em cp1252.
- **Tachados:** `<strike>`, `<s>`, `<del>` e `style="…line-through…"` → `~~texto~~`, mesma convenção do `corpus/INDICE.md`. Pares `~~~~` vazios removidos.
- **Espaços:** sequências de espaços/tabs colapsadas em um; linhas em branco consecutivas colapsadas; `Art.` separado do número por quebra de linha foi rejoined (`Art.\n1.793.` → `Art. 1.793.`). **Nenhuma palavra, número, pontuação ou marcador de alteração foi alterado** — verificado na seção anterior.
- **Marcadores preservados como a fonte os exibe:** "(Redação dada pela…)", "(Incluído pelo…)", "(Revogado…)", "(Vide …)", "(NR)", notas de renumeração. Nenhuma interpretação foi inserida dentro dos blocos; o que é análise desta lane está **fora** das cercas de código, nos cabeçalhos e neste índice.
- **User-Agent** `Mozilla/5.0`; timeout 120 s; `curl -sS -L`. Nenhuma fonte bloqueou (5/5 HTTP 200), portanto não houve necessidade de rota alternativa.
- **Estrutura de cada anexo:** cabeçalho no formato do `corpus/` (URL oficial, data 30/09/2026, comando usado, HTTP, bytes, nº de artigos, notas de extração) → blocos verbatim em cerca de código, um por grupo de artigos, com o cabeçalho estrutural da própria fonte (TÍTULO/CAPÍTULO/Seção) quando imediatamente anterior → seção "Contagem" ao fim, bloco a bloco.
- **Recorte literal ≠ diploma integral:** os cinco anexos dizem isso no cabeçalho, conforme exige o manifesto.

---

## Cautelas do manifesto — onde foram aplicadas

| Cautela do `ACHADOS-CORPUS.md` | Como foi cumprida |
|---|---|
| "**Não chamar 1.829 de herdeiros necessários**" | O art. 1.829 foi capturado em bloco próprio, com o cabeçalho da fonte "**CAPÍTULO I — Da Ordem da Vocação Hereditária**". Os herdeiros necessários estão em bloco separado, "**CAPÍTULO II — Dos Herdeiros Necessários**" (arts. 1.845–1.850). A distinção ficou estrutural, não apenas em nota. O título do bloco do 1.829 no anexo diz "ordem da vocação hereditária (sucessão legítima)" |
| "não aplicar dúvida registral ao tabelião automaticamente" | Nota no cabeçalho do anexo 3, transcrevendo o alcance do art. 296 (registros do art. 1º, § 1º, I a III) e afirmando expressamente que o recorte **não** cria rito de dúvida para o tabelião de notas |
| "não apagar texto histórico nem fazê-lo regra vigente" | Anexo 5 traz o diploma **integral**, sem supressão, com nota externa obrigatória que identifica os arts. 982/983/1.031/1.124-A como dispositivos do **CPC/1973 revogado**, aponta o CPC/2015 (arts. 610, 611, 731–733) como regime vigente e alerta que o prazo "60 dias / 12 meses" do art. 983 **não** é o vigente |
| "Recorte literal identificado não deve ser apresentado como diploma integral" | Os cinco cabeçalhos abrem com "Recorte literal, **não** é o diploma integral" |
| "preservar texto, revogações, artigo, URL, data, versão/publicação e notas de extração" | URL, HTTP, bytes, data, comando, decodificação e notas em todos os cabeçalhos; revogações/tachados preservados onde existem (Lei 8.935) e declarada a ausência onde não existem (CPC, CC, LRP, Lei 11.441) |
| "Corpus recebido permanece intacto" | `corpus/` não foi lido para escrita nem modificado; apenas consultado para espelhar o formato. Verificado: nenhum arquivo fora de `context-draft/` foi alterado por esta lane |

---

## O que esta lane NÃO fez

- **Não interpretou, não resumiu e não opinou** sobre nenhum dispositivo. A tarefa era captura; análise jurídica pertence às frentes F1–F5 e ao `ACHADOS-CORPUS.md`.
- **Não decidiu qual versão do art. 42-A da Lei 8.935 vigora**, nem rastreou a MP 1.085/2021.
- **Não leu** os REs 646.721 e 878.694 que a página do CC marca com "(Vide …)" no art. 1.829; os marcadores foram copiados como estão, sem atribuir tese, alcance ou situação às decisões.
- **Não verificou vigência em DOU / in.gov.br.** Todas as cinco fontes são as páginas compiladas ou integrais do Planalto na data da captura; não houve conferência cruzada contra publicação oficial nem busca de ato posterior que as páginas ainda não reflitam.
- **Não capturou os anexos de outras lanes** listados no manifesto (Res. 35/571/695, Prov. 149/202/56, CNN, LC 227, CF 155, CTN, Res. Senado 9/1992, Lei 10.169, Lei 15.040, LGPD, Estatuto e Código de Ética da OAB). Os cinco anexos desta lane são exatamente os atribuídos pelo brief CX-B.
- **Não ampliou recorte por conta própria.** Onde o manifesto pedia artigo específico, só ele foi capturado; onde pedia "e seguintes", a fronteira foi resolvida pela estrutura de capítulos da fonte e documentada. Remissões internas não pedidas (LRP 188, 1º § 1º, 149, 293; Lei 8.935 art. 33; CPC arts. 647–658 e 1.045) foram **declaradas como pendência**, não incluídas.
- **Nenhum `git commit`, nenhum `git push`, nenhuma edição fora de `context-draft/`.** Intermediários (HTML baixado e `.txt` de extração) ficaram em `/tmp/cxb/`, fora de qualquer repositório.
