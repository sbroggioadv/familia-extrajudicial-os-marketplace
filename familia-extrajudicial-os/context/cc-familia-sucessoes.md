# Código Civil — Lei nº 10.406/2002 (texto compilado) · recorte família e sucessões

- **URL oficial:** https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm
- **Data da captura:** 30/09/2026
- **Comando usado:** `curl -sS -L -A 'Mozilla/5.0' -m 120 -o cc.html 'https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm'` + extração com `html.parser` (stdlib), decodificação `cp1252`
- **HTTP:** 200 · **HTML baixado:** 923899 bytes · **Texto extraído:** 647239 caracteres
- **Artigos capturados:** 50 — lista bloco a bloco na seção "Contagem" ao fim
- **Notas de extração:** Recorte literal, **não** é o diploma integral. **Delimitação dos "e seguintes" do manifesto, resolvida pela estrutura da própria fonte:** "1.659 e seguintes do regime" = **arts. 1.658 a 1.666**, porque o "CAPÍTULO III — Do Regime de Comunhão Parcial" começa imediatamente antes do art. 1.658 e o art. 1.667 já abre o regime de comunhão universal. "1.845 e seguintes" = **arts. 1.845 a 1.850** ("CAPÍTULO II — Dos Herdeiros Necessários"), acrescidos dos **arts. 1.851 a 1.856** ("CAPÍTULO III — Do Direito de Representação"), porque o art. 1.856 trata expressamente do renunciante e o art. 1.811 remete à representação; a captura para no início do TÍTULO III (sucessão testamentária). **Cautela do manifesto preservada:** o art. 1.829 está no CAPÍTULO I (ordem da vocação hereditária) e **não** é a norma dos herdeiros necessários — estes estão no CAPÍTULO II, arts. 1.845 a 1.850; os dois blocos foram capturados separadamente, com os cabeçalhos estruturais da fonte, para que a distinção fique visível no texto. Marcadores "(Vide Recurso Extraordinário nº 646.721)" e "(Vide Recurso Extraordinário nº 878.694)" que a fonte oficial exibe ao lado do caput do art. 1.829 foram **preservados como estão**, sem atribuição de tese. Tachados seriam convertidos para `~~texto~~`; **verificado: nenhum trecho tachado/revogado existe dentro dos 50 artigos capturados**, que estão na redação vigente da página compilada. Marcadores de alteração ("Redação dada pela…") e remissões "(Vide …)" preservados como a fonte os exibe. Verificar sempre se há revogação posterior no próprio texto capturado antes de usar. Fidelidade conferida parágrafo a parágrafo contra o texto bruto da fonte: **127/127 parágrafos ≥60 caracteres literalmente presentes** (ver `INDICE-B.md`).


## Art. 104 — validade do negócio jurídico

```
CAPÍTULO
I
 Disposições Gerais
 Art. 104. A validade do negócio jurídico requer:
 I - agente capaz;
 II - objeto lícito, possível, determinado ou determinável;
 III - forma prescrita ou não defesa em lei.
```

## Art. 108 — escritura pública como forma essencial

```
Art. 108. Não dispondo a lei em contrário, a escritura pública
é essencial à validade dos negócios jurídicos que visem à constituição,
transferência, modificação ou renúncia de direitos reais sobre imóveis de valor
superior a trinta vezes o maior salário mínimo vigente no País.
```

## Art. 215 — escritura pública e fé pública

```
Art. 215. A escritura pública, lavrada em notas de tabelião, é documento dotado de
fé pública, fazendo prova plena.
 § 1
 o
 Salvo quando exigidos por lei outros requisitos, a escritura
pública deve conter:
 I - data e local de sua realização;
 II - reconhecimento da identidade e capacidade das partes e de quantos hajam
comparecido ao ato, por si, como representantes, intervenientes ou testemunhas;
 III - nome, nacionalidade, estado civil, profissão, domicílio e residência das
partes e demais comparecentes, com a indicação, quando necessário, do regime de bens do
casamento, nome do outro cônjuge e filiação;
 IV - manifestação clara da vontade das partes e dos intervenientes;
 V - referência ao cumprimento das exigências legais e fiscais inerentes à
legitimidade do ato;
 VI - declaração de ter sido lida na presença das partes e demais comparecentes, ou
de que todos a leram;
 VII - assinatura das partes e dos demais comparecentes, bem como a do tabelião ou seu
substituto legal, encerrando o ato.
 § 2
 o
 Se algum comparecente não puder ou não souber escrever, outra
pessoa capaz assinará por ele, a seu rogo.
 § 3
 o
 A escritura será redigida na língua nacional.
 § 4
 o
 Se qualquer dos comparecentes não souber a língua nacional e
o tabelião não entender o idioma em que se expressa, deverá comparecer tradutor
público para servir de intérprete, ou, não o havendo na localidade, outra pessoa capaz
que, a juízo do tabelião, tenha idoneidade e conhecimento bastantes.
 § 5
 o
 Se algum dos comparecentes não for conhecido do tabelião, nem
puder identificar-se por documento, deverão participar do ato pelo menos duas testemunhas
que o conheçam e atestem sua identidade.
```

## Art. 657 — forma do mandato

```
Art. 657. A outorga do mandato está sujeita à forma exigida por lei para o ato a ser
praticado. Não se admite mandato verbal quando o ato deva ser celebrado por escrito.
```

## Art. 661 — mandato em termos gerais e poderes para alienar

```
Art. 661. O mandato em termos gerais só confere poderes de administração.
 § 1
 o
 Para alienar, hipotecar, transigir, ou praticar outros
quaisquer atos que exorbitem da administração ordinária, depende a procuração de
poderes especiais e expressos.
 § 2
 o
 O poder de transigir não importa o de firmar compromisso.
```

## Art. 1.571 — extinção da sociedade conjugal

```
CAPÍTULO X
 Da Dissolução da Sociedade e do vínculo Conjugal
 Art. 1.571. A sociedade conjugal termina:
 I - pela morte de um dos cônjuges;
 II - pela nulidade ou anulação do casamento;
 III - pela separação judicial;
 IV - pelo divórcio.
 § 1
 o
 O casamento válido só se dissolve pela morte de um dos
cônjuges ou pelo divórcio, aplicando-se a presunção estabelecida neste Código quanto
ao ausente.
 § 2
 o
 Dissolvido o casamento pelo divórcio direto ou por conversão,
o cônjuge poderá manter o nome de casado; salvo, no segundo caso, dispondo em contrário
a sentença de separação judicial.
```

## Art. 1.581 — divórcio sem prévia partilha

```
Art. 1.581. O divórcio pode ser concedido sem que haja prévia partilha de bens.
```

## Arts. 1.640 a 1.641 — regime supletivo e separação obrigatória

```
Art. 1.640. Não havendo convenção, ou sendo ela nula ou ineficaz, vigorará, quanto
aos bens entre os cônjuges, o regime da comunhão parcial.
 Parágrafo único. Poderão os nubentes, no processo de habilitação, optar por
qualquer dos regimes que este código regula. Quanto à forma, reduzir-se-á a termo a
opção pela comunhão parcial, fazendo-se o pacto antenupcial por escritura pública, nas
demais escolhas.
 Art. 1.641. É obrigatório o regime da separação de bens no casamento:
 I - das pessoas que o contraírem com inobservância das causas suspensivas da
celebração do casamento;
 II – da pessoa maior de 70 (setenta) anos;
 (Redação dada pela Lei nº 
12.344, de 2010)
 III - de todos os que dependerem, para casar, de suprimento judicial.
```

## Art. 1.653 — forma do pacto antenupcial

```
CAPÍTULO II
 Do Pacto Antenupcial
 Art. 1.653. É nulo o pacto antenupcial se não for feito por escritura pública, e
ineficaz se não lhe seguir o casamento.
```

## Art. 1.657 — convenções antenupciais perante terceiros

```
Art. 1.657. As convenções antenupciais não terão efeito perante terceiros senão
depois de registradas, em livro especial, pelo oficial do Registro de Imóveis do
domicílio dos cônjuges.
 CAPÍTULO III
 Do Regime de Comunhão Parcial
```

## CAPÍTULO III — Do Regime de Comunhão Parcial (arts. 1.658 a 1.666, integral)

```
CAPÍTULO III
 Do Regime de Comunhão Parcial
 Art. 1.658. No regime de comunhão parcial, comunicam-se os bens que sobrevierem ao
casal, na constância do casamento, com as exceções dos artigos seguintes.
 Art. 1.659. Excluem-se da comunhão:
 I - os bens que cada cônjuge possuir ao casar, e os que lhe sobrevierem, na
constância do casamento, por doação ou sucessão, e os sub-rogados em seu lugar;
 II - os bens adquiridos com valores exclusivamente pertencentes a um dos cônjuges em
sub-rogação dos bens particulares;
 III - as obrigações anteriores ao casamento;
 IV - as obrigações provenientes de atos ilícitos, salvo reversão em proveito do
casal;
 V - os bens de uso pessoal, os livros e instrumentos de profissão;
 VI - os proventos do trabalho pessoal de cada cônjuge;
 VII - as pensões, meios-soldos, montepios e outras rendas semelhantes.
 Art. 1.660. Entram na comunhão:
 I - os bens adquiridos na constância do casamento por título oneroso, ainda que só
em nome de um dos cônjuges;
 II - os bens adquiridos por fato eventual, com ou sem o concurso de trabalho ou despesa
anterior;
 III - os bens adquiridos por doação, herança ou legado, em favor de ambos os
cônjuges;
 IV - as benfeitorias em bens particulares de cada cônjuge;
 V - os frutos dos bens comuns, ou dos particulares de cada cônjuge, percebidos na
constância do casamento, ou pendentes ao tempo de cessar a comunhão.
 Art. 1.661. São incomunicáveis os bens cuja aquisição tiver por título uma causa
anterior ao casamento.
 Art. 1.662. No regime da comunhão parcial, presumem-se adquiridos na constância do
casamento os bens móveis, quando não se provar que o foram em data anterior.
 Art. 1.663. A administração do patrimônio comum compete a qualquer dos cônjuges.
 § 1
 o
 As dívidas contraídas no exercício da administração
obrigam os bens comuns e particulares do cônjuge que os administra, e os do outro na
razão do proveito que houver auferido.
 § 2
 o
 A anuência de ambos os cônjuges é necessária para os atos,
a título gratuito, que impliquem cessão do uso ou gozo dos bens comuns.
 § 3
 o
 Em caso de malversação dos bens, o juiz poderá atribuir a
administração a apenas um dos cônjuges.
 Art. 1.664. Os bens da comunhão respondem pelas obrigações contraídas pelo marido
ou pela mulher para atender aos encargos da família, às despesas de administração e
às decorrentes de imposição legal.
 Art. 1.665. A administração e a disposição dos bens constitutivos do patrimônio
particular competem ao cônjuge proprietário, salvo convenção diversa em pacto
antenupcial.
 Art. 1.666. As dívidas, contraídas por qualquer dos cônjuges na administração de
seus bens particulares e em benefício destes, não obrigam os bens comuns.
 CAPÍTULO IV
 Do Regime de Comunhão Universal
```

## Arts. 1.723 a 1.727 — união estável

```
TÍTULO III
 DA UNIÃO ESTÁVEL
 Art. 1.723. É reconhecida como entidade familiar a união estável entre o homem e a
mulher, configurada na convivência pública, contínua e duradoura e estabelecida com o
objetivo de constituição de família.
 § 1
 o
 A união estável não se constituirá se ocorrerem os
impedimentos do art. 1.521; não se aplicando a incidência do inciso VI no caso de a
pessoa casada se achar separada de fato ou judicialmente.
 § 2
 o
 As causas suspensivas do art. 1.523 não impedirão a
caracterização da união estável.
 Art. 1.724. As relações pessoais entre os companheiros obedecerão aos deveres de
lealdade, respeito e assistência, e de guarda, sustento e educação dos filhos.
 Art. 1.725. Na união estável, salvo contrato escrito entre os companheiros, aplica-se
às relações patrimoniais, no que couber, o regime da comunhão parcial de bens.
 Art. 1.726. A união estável poderá converter-se em casamento, mediante pedido dos
companheiros ao juiz e assento no Registro Civil.
 Art. 1.727. As relações não eventuais entre o homem e a mulher, impedidos de casar,
constituem concubinato.
 TÍTULO IV
 Da Tutela, da Curatela e da Tomada de 
 Decisão Apoiada
 (Redação 
 dada pela Lei nº 13.146, de 
2015)
 CAPÍTULO I
 Da Tutela
 Seção I
 Dos Tutores
```

## Arts. 1.793 a 1.795 — cessão de direitos hereditários

```
Art. 1.793. O direito à sucessão aberta, bem como o quinhão de que disponha o
co-herdeiro, pode ser objeto de cessão por escritura pública.
 § 1
 o
 Os direitos, conferidos ao herdeiro em conseqüência de
substituição ou de direito de acrescer, presumem-se não abrangidos pela cessão feita
anteriormente.
 § 2
 o
 É ineficaz a cessão, pelo co-herdeiro, de seu direito
hereditário sobre qualquer bem da herança considerado singularmente.
 § 3
 o
 Ineficaz é a disposição, sem prévia autorização do juiz
da sucessão, por qualquer herdeiro, de bem componente do acervo hereditário, pendente a
indivisibilidade.
 Art. 1.794. O co-herdeiro não poderá ceder a sua quota hereditária a pessoa estranha
à sucessão, se outro co-herdeiro a quiser, tanto por tanto.
 Art. 1.795. O co-herdeiro, a quem não se der conhecimento da cessão, poderá,
depositado o preço, haver para si a quota cedida a estranho, se o requerer até cento e
oitenta dias após a transmissão.
 Parágrafo único. Sendo vários os co-herdeiros a exercer a preferência, entre eles
se distribuirá o quinhão cedido, na proporção das respectivas quotas hereditárias.
```

## Arts. 1.806 a 1.813 — aceitação e renúncia da herança

```
Art. 1.806. A renúncia da herança deve constar expressamente de instrumento público
ou termo judicial.
 Art. 1.807. O interessado em que o herdeiro declare se aceita, ou não, a herança,
poderá, vinte dias após aberta a sucessão, requerer ao juiz prazo razoável, não maior
de trinta dias, para, nele, se pronunciar o herdeiro, sob pena de se haver a herança por
aceita.
 Art. 1.808. Não se pode aceitar ou renunciar a herança em parte, sob condição ou a
termo.
 § 1
 o
 O herdeiro, a quem se testarem legados, pode aceitá-los,
renunciando a herança; ou, aceitando-a, repudiá-los.
 § 2
 o
 O herdeiro, chamado, na mesma sucessão, a mais de um quinhão
hereditário, sob títulos sucessórios diversos, pode livremente deliberar quanto aos
quinhões que aceita e aos que renuncia.
 Art. 1.809. Falecendo o herdeiro antes de declarar se aceita a herança, o poder de
aceitar passa-lhe aos herdeiros, a menos que se trate de vocação adstrita a uma
condição suspensiva, ainda não verificada.
 Parágrafo único. Os chamados à sucessão do herdeiro falecido antes da aceitação,
desde que concordem em receber a segunda herança, poderão aceitar ou renunciar a
primeira.
 Art. 1.810. Na sucessão legítima, a parte do renunciante acresce à dos outros
herdeiros da mesma classe e, sendo ele o único desta, devolve-se aos da subseqüente.
 Art. 1.811. Ninguém pode suceder, representando herdeiro renunciante. Se, porém, ele
for o único legítimo da sua classe, ou se todos os outros da mesma classe renunciarem a
herança, poderão os filhos vir à sucessão, por direito próprio, e por cabeça.
 Art. 1.812. São irrevogáveis os atos de aceitação ou de renúncia da herança.
 Art. 1.813. Quando o herdeiro prejudicar os seus credores, renunciando à herança,
poderão eles, com autorização do juiz, aceitá-la em nome do renunciante.
 § 1
 o
 A habilitação dos credores se fará no prazo de trinta dias
seguintes ao conhecimento do fato.
 § 2
 o
 Pagas as dívidas do renunciante, prevalece a renúncia quanto
ao remanescente, que será devolvido aos demais herdeiros.
 CAPÍTULO V
 Dos Excluídos da Sucessão
```

## CAPÍTULO I — Art. 1.829 — ordem da vocação hereditária (sucessão legítima)

```
CAPÍTULO I
 Da Ordem da Vocação Hereditária
 Art. 1.829. A sucessão legítima defere-se na ordem seguinte:
 (Vide Recurso Extraordinário nº 646.721)
 (Vide Recurso Extraordinário nº 878.694)
 I - aos descendentes, em concorrência com o cônjuge sobrevivente, salvo se casado
este com o falecido no regime da comunhão universal, ou no da separação obrigatória de
bens (art. 1.640, parágrafo único); ou se, no regime da comunhão parcial, o autor da
herança não houver deixado bens particulares;
 II - aos ascendentes, em concorrência com o cônjuge;
 III - ao cônjuge sobrevivente;
 IV - aos colaterais.
```

## CAPÍTULO II — Dos Herdeiros Necessários (arts. 1.845 a 1.850, integral)

```
CAPÍTULO II
 Dos Herdeiros Necessários
 Art. 1.845. São herdeiros necessários os descendentes, os ascendentes e o cônjuge.
 Art. 1.846. Pertence aos herdeiros necessários, de pleno direito, a metade dos bens da
herança, constituindo a legítima.
 Art. 1.847. Calcula-se a legítima sobre o valor dos bens existentes na abertura da
sucessão, abatidas as dívidas e as despesas do funeral, adicionando-se, em seguida, o
valor dos bens sujeitos a colação.
 Art. 1.848. Salvo se houver justa causa, declarada no testamento, não pode o testador
estabelecer cláusula de inalienabilidade, impenhorabilidade, e de incomunicabilidade,
sobre os bens da legítima.
 § 1
 o
 Não é permitido ao testador estabelecer a conversão dos bens
da legítima em outros de espécie diversa.
 § 2
 o
 Mediante autorização judicial e havendo justa causa, podem
ser alienados os bens gravados, convertendo-se o produto em outros bens, que ficarão
sub-rogados nos ônus dos primeiros.
 Art. 1.849. O herdeiro necessário, a quem o testador deixar a sua parte disponível,
ou algum legado, não perderá o direito à legítima.
 Art. 1.850. Para excluir da sucessão os herdeiros colaterais, basta que o testador
disponha de seu patrimônio sem os contemplar.
 CAPÍTULO III
 Do Direito de Representação
```

## CAPÍTULO III — Do Direito de Representação (arts. 1.851 a 1.856, integral)

```
CAPÍTULO III
 Do Direito de Representação
 Art. 1.851. Dá-se o direito de representação, quando a lei chama certos parentes do
falecido a suceder em todos os direitos, em que ele sucederia, se vivo fosse.
 Art. 1.852. O direito de representação dá-se na linha reta descendente, mas nunca na
ascendente.
 Art. 1.853. Na linha transversal, somente se dá o direito de representação em favor
dos filhos de irmãos do falecido, quando com irmãos deste concorrerem.
 Art. 1.854. Os representantes só podem herdar, como tais, o que herdaria o
representado, se vivo fosse.
 Art. 1.855. O quinhão do representado partir-se-á por igual entre os representantes.
 Art. 1.856. O renunciante à herança de uma pessoa poderá representá-la na sucessão
de outra.
 TITULO III
 DA SUCESSÃO TESTAMENTÁRIA
 CAPITULO I
 DO TESTAMENTO EM GERAL
```

## Art. 2.015 — partilha amigável

```
Art. 2.015. Se os herdeiros forem capazes, poderão fazer partilha amigável, por
escritura pública, termo nos autos do inventário, ou escrito particular, homologado pelo
juiz.
```

---

## Contagem

| Bloco | Artigos capturados | nº |
|---|---|---:|
| Art. 104 — validade do negócio jurídico | 104 | 1 |
| Art. 108 — escritura pública como forma essencial | 108 | 1 |
| Art. 215 — escritura pública e fé pública | 215 | 1 |
| Art. 657 — forma do mandato | 657 | 1 |
| Art. 661 — mandato em termos gerais e poderes para alienar | 661 | 1 |
| Art. 1.571 — extinção da sociedade conjugal | 1.571 | 1 |
| Art. 1.581 — divórcio sem prévia partilha | 1.581 | 1 |
| Arts. 1.640 a 1.641 — regime supletivo e separação obrigatória | 1.640, 1.641 | 2 |
| Art. 1.653 — forma do pacto antenupcial | 1.653 | 1 |
| Art. 1.657 — convenções antenupciais perante terceiros | 1.657 | 1 |
| CAPÍTULO III — Do Regime de Comunhão Parcial (arts. 1.658 a 1.666, integral) | 1.658, 1.659, 1.660, 1.661, 1.662, 1.663, 1.664, 1.665, 1.666 | 9 |
| Arts. 1.723 a 1.727 — união estável | 1.723, 1.724, 1.725, 1.726, 1.727 | 5 |
| Arts. 1.793 a 1.795 — cessão de direitos hereditários | 1.793, 1.794, 1.795 | 3 |
| Arts. 1.806 a 1.813 — aceitação e renúncia da herança | 1.806, 1.807, 1.808, 1.809, 1.810, 1.811, 1.812, 1.813 | 8 |
| CAPÍTULO I — Art. 1.829 — ordem da vocação hereditária (sucessão legítima) | 1.829 | 1 |
| CAPÍTULO II — Dos Herdeiros Necessários (arts. 1.845 a 1.850, integral) | 1.845, 1.846, 1.847, 1.848, 1.849, 1.850 | 6 |
| CAPÍTULO III — Do Direito de Representação (arts. 1.851 a 1.856, integral) | 1.851, 1.852, 1.853, 1.854, 1.855, 1.856 | 6 |
| Art. 2.015 — partilha amigável | 2.015 | 1 |
| **Total (sem repetição)** | | **50** |

---

## CX-D — acréscimo 30/09/2026 · arts. 2.016 e 2.017 (RDS1 G1)

- **URL oficial (a mesma da captura CX-B):** https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm
- **Data da captura (CX-D):** 30/09/2026
- **Comando usado:** `curl -sS -L -A 'Mozilla/5.0' -m 120 -o /tmp/cxd-raw/cc.html 'https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm'` + extração com `html.parser` (stdlib), decodificação `cp1252`
- **HTTP:** 200 · **HTML baixado:** 923899 bytes
- **Notas:** Acréscimo **somente ao final**. Cabeçalho CX-B («50 artigos») e tabela Contagem **não foram alterados**. O art. 2.016 vem imediatamente após o art. 2.015 na fonte; o art. 2.017 vem junto, imediatamente a seguir. Recorte pára **antes** do art. 2.018 (partilha por ascendente). Fidelidade: os dois parágrafos ≥60 caracteres estão literalmente no texto bruto da fonte.

## Art. 2.016 — partilha judicial se divergência ou incapaz

```
Art. 2.016. Será sempre judicial a partilha, se os herdeiros divergirem, assim como se
algum deles for incapaz.
```

## Art. 2.017 — igualdade na partilha

```
Art. 2.017. No partilhar os bens, observar-se-á, quanto ao seu valor, natureza e
qualidade, a maior igualdade possível.
```


---

## FB — acréscimo 01/10/2026 · art. 1.911 (RC5 G1)

- **URL oficial:** https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm
- **Data da captura:** 01/10/2026
- **Comando usado:** `curl -sS -L -A 'Mozilla/5.0' -m 45 -D /tmp/fb-cc-headers.txt -o /tmp/fb-cc.html 'https://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm'`; extração com `html.parser` (stdlib), decodificação `cp1252`, normalização somente de espaços/quebras.
- **HTTP:** 200 · **HTML baixado:** 923899 bytes
- **SHA-256 do HTML:** `16de2aae738bd61f4d20d0d5dc594644186d6ad43846cb08f1e59e38ab771527`
- **Delimitação:** caput e parágrafo único do art. 1.911, encerrados antes do CAPÍTULO VII — Dos Legados. Acréscimo ao final; capturas e contagens históricas preservadas. Não é fundamento de cessão hereditária.
- **Fidelidade:** caput e parágrafo único literalmente iguais à fonte após normalização somente de espaços/quebras; sem caracteres de controle, invisíveis ou de substituição.

### Art. 1.911 — cláusula de inalienabilidade

```
Art. 1.911. A cláusula de inalienabilidade, imposta aos bens por ato de liberalidade, implica impenhorabilidade e incomunicabilidade.

Parágrafo único. No caso de desapropriação de bens clausulados, ou de sua alienação, por conveniência econômica do donatário ou do herdeiro, mediante autorização judicial, o produto da venda converter-se-á em outros bens, sobre os quais incidirão as restrições apostas aos primeiros.
```
