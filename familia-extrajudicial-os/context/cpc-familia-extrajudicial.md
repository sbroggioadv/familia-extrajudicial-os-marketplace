# CPC — Lei nº 13.105/2015 · recorte família e sucessões extrajudiciais

- **URL oficial:** http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13105.htm
- **Data da captura:** 30/09/2026
- **Comando usado:** `curl -sS -L -A 'Mozilla/5.0' -m 120 -o cpc.html 'http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13105.htm'` + extração com `html.parser` (stdlib), decodificação `cp1252`
- **HTTP:** 200 · **HTML baixado:** 1691185 bytes · **Texto extraído:** 593923 caracteres
- **Artigos capturados:** 7 — lista bloco a bloco na seção "Contagem" ao fim
- **Notas de extração:** Recorte literal, **não** é o diploma integral. Capturados 610, 611, 617, 731, 732, 733 e 1.046, conforme o manifesto de anexos do ACHADOS-CORPUS.md (linha `cpc-familia-extrajudicial.md`: "610/611/731–733/1.046; 617 se houver comparação judicial"). **Fronteira declarada:** os arts. 647 a 658 (partilha judicial, para onde o art. 731, parágrafo único, remete em caso de desacordo) **não** foram capturados — o manifesto os admite "só como fronteira, sem importar peças judiciais". Nenhum artigo foi reescrito; marcadores de alteração ("Redação dada…", "Incluído…", "Vide…") e tachados (`~~texto~~`) foram preservados como estão na fonte. **Verificado: nenhum trecho tachado/revogado existe dentro dos sete artigos capturados** — os recortes estão na redação vigente da página. O **art. 1.045** (vigência do CPC), imediatamente anterior ao 1.046, **não** foi capturado: está fora do recorte pedido pelo manifesto. Fidelidade conferida parágrafo a parágrafo contra o texto bruto da fonte: **26/26 parágrafos ≥60 caracteres literalmente presentes** (ver `INDICE-B.md`).


## Arts. 610 a 611 — inventário e partilha: cabimento, forma e prazo

```
Seção I
 Disposições Gerais
 Art. 610. Havendo testamento ou interessado incapaz, proceder-se-á ao inventário judicial.
 § 1º Se todos forem capazes e concordes, o inventário e a partilha poderão ser feitos por escritura pública, a qual constituirá documento hábil para qualquer ato de registro, bem como para levantamento de importância depositada em instituições financeiras.
 § 2
 o
 O tabelião somente lavrará a escritura pública se todas as partes interessadas estiverem assistidas por advogado ou por defensor público, cuja qualificação e assinatura constarão do ato notarial.
 Art. 611. O processo de inventário e de partilha deve ser instaurado dentro de 2 (dois) meses, a contar da abertura da sucessão, ultimando-se nos 12 (doze) meses subsequentes, podendo o juiz prorrogar esses prazos, de ofício ou a requerimento de parte.
```

## Art. 617 — ordem de nomeação do inventariante na via judicial (capturado para contraste com a Res. CNJ 35, art. 11)

```
Seção III
 Do Inventariante e das Primeiras Declarações
 Art. 617. O juiz nomeará inventariante na seguinte ordem:
 I - o cônjuge ou companheiro sobrevivente, desde que estivesse convivendo com o outro ao tempo da morte deste;
 II - o herdeiro que se achar na posse e na administração do espólio, se não houver cônjuge ou companheiro sobrevivente ou se estes não puderem ser nomeados;
 III - qualquer herdeiro, quando nenhum deles estiver na posse e na administração do espólio;
 IV - o herdeiro menor, por seu representante legal;
 V - o testamenteiro, se lhe tiver sido confiada a administração do espólio ou se toda a herança estiver distribuída em legados;
 VI - o cessionário do herdeiro ou do legatário;
 VII - o inventariante judicial, se houver;
 VIII - pessoa estranha idônea, quando não houver inventariante judicial.
 Parágrafo único. O inventariante, intimado da nomeação, prestará, dentro de 5 (cinco) dias, o compromisso de bem e fielmente desempenhar a função.
```

## Arts. 731 a 733 — divórcio, separação e extinção consensual de união estável

```
Seção IV
 Do Divórcio e da Separação Consensuais, da Extinção Consensual de União Estável e da Alteração do Regime de Bens do Matrimônio
 Art. 731. A homologação do divórcio ou da separação consensuais, observados os requisitos legais, poderá ser requerida em petição assinada por ambos os cônjuges, da qual constarão:
 I - as disposições relativas à descrição e à partilha dos bens comuns;
 II - as disposições relativas à pensão alimentícia entre os cônjuges;
 III - o acordo relativo à guarda dos filhos incapazes e ao regime de visitas; e
 IV - o valor da contribuição para criar e educar os filhos.
 Parágrafo único. Se os cônjuges não acordarem sobre a partilha dos bens, far-se-á esta depois de homologado o divórcio, na forma estabelecida nos
 arts. 647
 a
 658
 .
 Art. 732. As disposições relativas ao processo de homologação judicial de divórcio ou de separação consensuais aplicam-se, no que couber, ao processo de homologação da extinção consensual de união estável.
 Art. 733. O divórcio consensual, a separação consensual e a extinção consensual de união estável, não havendo nascituro ou filhos incapazes e observados os requisitos legais, poderão ser realizados por escritura pública, da qual constarão as disposições de que trata o
 art. 731
 .
 § 1º A escritura não depende de homologação judicial e constitui título hábil para qualquer ato de registro, bem como para levantamento de importância depositada em instituições financeiras.
 § 2º O tabelião somente lavrará a escritura se os interessados estiverem assistidos por advogado ou por defensor público, cuja qualificação e assinatura constarão do ato notarial.
```

## Art. 1.046 — disposição de transição

```
Art. 1.046. Ao entrar em vigor este Código, suas disposições se aplicarão desde logo aos processos pendentes, ficando revogada a
 Lei nº 5.869, de 11 de janeiro de 1973.
 § 1º As disposições da
 Lei nº 5.869, de 11 de janeiro de 1973
 , relativas ao procedimento sumário e aos procedimentos especiais que forem revogadas aplicar-se-ão às ações propostas e não sentenciadas até o início da vigência deste Código.
 § 2º Permanecem em vigor as disposições especiais dos procedimentos regulados em outras leis, aos quais se aplicará supletivamente este Código.
 § 3º Os processos mencionados no
 art. 1.218 da Lei nº 5.869, de 11 de janeiro de 1973
 , cujo procedimento ainda não tenha sido incorporado por lei submetem-se ao procedimento comum previsto neste Código.
 § 4º As remissões a disposições do Código de Processo Civil revogado, existentes em outras leis, passam a referir-se às que lhes são correspondentes neste Código.
 § 5º A primeira lista de processos para julgamento em ordem cronológica observará a antiguidade da distribuição entre os já conclusos na data da entrada em
 vigor deste Código
 .
```

---

## Contagem

| Bloco | Artigos capturados | nº |
|---|---|---:|
| Arts. 610 a 611 — inventário e partilha: cabimento, forma e prazo | 610, 611 | 2 |
| Art. 617 — ordem de nomeação do inventariante na via judicial (capturado para contraste com a Res. CNJ 35, art. 11) | 617 | 1 |
| Arts. 731 a 733 — divórcio, separação e extinção consensual de união estável | 731, 732, 733 | 3 |
| Art. 1.046 — disposição de transição | 1.046 | 1 |
| **Total (sem repetição)** | | **7** |
