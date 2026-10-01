# Lei nº 13.709, de 14 de agosto de 2018 — LGPD (dados sensíveis e bases de tratamento em processo)

- **URL oficial:** https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm
- **Data da captura:** 30/09/2026
- **Comando usado:** `curl -sS -L -A 'Mozilla/5.0' -o /tmp/cxc-raw/lgpdcomp.html https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm && python3 HTMLParser→txt`
- **Notas:** html2text não instalado; conversão por HTMLParser (stdlib) com <strike>/<s>/<del>/line-through → ~~texto~~. Encoding iso-8859-1 quando UTF-8 falha (Planalto). Recorte da LGPD vigente (página compilada): arts. 5º (II = dado pessoal sensível), 6º (princípios), 7º (bases, inclusive VI — exercício regular de direitos em processo judicial, administrativo ou arbitral) e 11 (dados sensíveis, inclusive II, d — exercício regular de direitos em contrato e em processo). A fonte não usa a palavra «advogado»; o tratamento por advogado no diploma está nesses dispositivos de processo/direitos. Também baixada a página não compilada l13709.htm (HTTP 200, 310.252 B). Compilado traz redação posterior do art. 5º, VIII e XIX (Lei nº 15.352/2026). §§ 1º e 2º do art. 7º constam como (Revogado).

## Art. 5º

```
Art. 5º Para os fins desta Lei, considera-se:

     I - dado pessoal: informação relacionada a pessoa natural identificada ou identificável;

     II - dado pessoal sensível: dado pessoal sobre origem racial ou étnica, convicção religiosa, opinião política, filiação a sindicato ou a organização de caráter religioso, filosófico ou político, dado referente à saúde ou à vida sexual, dado genético ou biométrico, quando vinculado a uma pessoa natural;

     III - dado anonimizado: dado relativo a titular que não possa ser identificado, considerando a utilização de meios técnicos razoáveis e disponíveis na ocasião de seu tratamento;

     IV - banco de dados: conjunto estruturado de dados pessoais, estabelecido em um ou em vários locais, em suporte eletrônico ou físico;

     V - titular: pessoa natural a quem se referem os dados pessoais que são objeto de tratamento;

     VI - controlador: pessoa natural ou jurídica, de direito público ou privado, a quem competem as decisões referentes ao tratamento de dados pessoais;

     VII - operador: pessoa natural ou jurídica, de direito público ou privado, que realiza o tratamento de dados pessoais em nome do controlador;

VIII - encarregado: pessoa indicada pelo controlador e operador para
atuar como canal de comunicação entre o controlador, os titulares dos
dados e a Agência Nacional de Proteção de Dados
(ANPD);
(Redação dada
pela Lei nº 15.352, de 2026)

     IX - agentes de tratamento: o controlador e o operador;

     X - tratamento: toda operação realizada com dados pessoais, como as que se referem a coleta, produção, recepção, classificação, utilização, acesso, reprodução, transmissão, distribuição, processamento, arquivamento, armazenamento, eliminação, avaliação ou controle da informação, modificação, comunicação, transferência, difusão ou extração;

     XI - anonimização: utilização de meios técnicos razoáveis e disponíveis no momento do tratamento, por meio dos quais um dado perde a possibilidade de associação, direta ou indireta, a um indivíduo;

     XII - consentimento: manifestação livre, informada e inequívoca pela qual o titular concorda com o tratamento de seus dados pessoais para uma finalidade determinada;

     XIII - bloqueio: suspensão temporária de qualquer operação de tratamento, mediante guarda do dado pessoal ou do banco de dados;

     XIV - eliminação: exclusão de dado ou de conjunto de dados armazenados em banco de dados, independentemente do procedimento empregado;

     XV - transferência internacional de dados: transferência de dados pessoais para país estrangeiro ou organismo internacional do qual o país seja membro;

     XVI - uso compartilhado de dados: comunicação, difusão, transferência internacional, interconexão de dados pessoais ou tratamento compartilhado de bancos de dados pessoais por órgãos e entidades públicos no cumprimento de suas competências legais, ou entre esses e entes privados, reciprocamente, com autorização específica, para uma ou mais modalidades de tratamento permitidas por esses entes públicos, ou entre entes privados;

     XVII - relatório de impacto à proteção de dados pessoais: documentação do controlador que contém a descrição dos processos de tratamento de dados pessoais que podem gerar riscos às liberdades civis e aos direitos fundamentais, bem como medidas, salvaguardas e mecanismos de mitigação de risco;

XVIII - órgão de pesquisa: órgão ou entidade da administração pública
direta ou indireta ou pessoa jurídica de direito privado sem fins
lucrativos legalmente constituída sob as leis brasileiras, com sede e
foro no País, que inclua em sua missão institucional ou em seu objetivo
social ou estatutário a pesquisa básica ou aplicada de caráter
histórico, científico, tecnológico ou estatístico; e
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

    XIX -
autoridade nacional: entidade da administração pública responsável por
zelar, implementar e
fiscalizar o
cumprimento desta
Lei em todo o território
nacional.

(Redação dada pela Lei nº 15.352, de 2026)
```

## Art. 6º

```
Art. 6º As atividades de tratamento de dados pessoais deverão observar a boa-fé e os seguintes princípios:

     I - finalidade: realização do tratamento para propósitos legítimos, específicos, explícitos e informados ao titular, sem possibilidade de tratamento posterior de forma incompatível com essas finalidades;

     II - adequação: compatibilidade do tratamento com as finalidades informadas ao titular, de acordo com o contexto do tratamento;

     III - necessidade: limitação do tratamento ao mínimo necessário para a realização de suas finalidades, com abrangência dos dados pertinentes, proporcionais e não excessivos em relação às finalidades do tratamento de dados;

     IV - livre acesso: garantia, aos titulares, de consulta facilitada e gratuita sobre a forma e a duração do tratamento, bem como sobre a integralidade de seus dados pessoais;

     V - qualidade dos dados: garantia, aos titulares, de exatidão, clareza, relevância e atualização dos dados, de acordo com a necessidade e para o cumprimento da finalidade de seu tratamento;

     VI - transparência: garantia, aos titulares, de informações claras, precisas e facilmente acessíveis sobre a realização do tratamento e os respectivos agentes de tratamento, observados os segredos comercial e industrial;

     VII - segurança: utilização de medidas técnicas e administrativas aptas a proteger os dados pessoais de acessos não autorizados e de situações acidentais ou ilícitas de destruição, perda, alteração, comunicação ou difusão;

     VIII - prevenção: adoção de medidas para prevenir a ocorrência de danos em virtude do tratamento de dados pessoais;

     IX - não discriminação: impossibilidade de realização do tratamento para fins discriminatórios ilícitos ou abusivos;

     X - responsabilização e prestação de contas: demonstração, pelo agente, da adoção de medidas eficazes e capazes de comprovar a observância e o cumprimento das normas de proteção de dados pessoais e, inclusive, da eficácia dessas medidas.
```

## Art. 7º

```
Art. 7º O tratamento de dados pessoais somente poderá ser realizado nas seguintes hipóteses:

     I - mediante o fornecimento de consentimento pelo titular;

     II - para o cumprimento de obrigação legal ou regulatória pelo controlador;

     III - pela administração pública, para o tratamento e uso compartilhado de dados necessários à execução de políticas públicas previstas em leis e regulamentos ou respaldadas em contratos, convênios ou instrumentos congêneres, observadas as disposições do Capítulo IV desta Lei;

     IV - para a realização de estudos por órgão de pesquisa, garantida, sempre que possível, a anonimização dos dados pessoais;

     V - quando necessário para a execução de contrato ou de procedimentos preliminares relacionados a contrato do qual seja parte o titular, a pedido do titular dos dados;

     VI - para o exercício regular de direitos em processo judicial, administrativo ou arbitral, esse último nos termos da

      Lei nº 9.307, de 23 de setembro de 1996 (Lei de Arbitragem)

     ;

     VII - para a proteção da vida ou da incolumidade física do titular ou de terceiro;

VIII - para a tutela da saúde, exclusivamente, em procedimento realizado
por profissionais de saúde, serviços de saúde ou autoridade sanitária;
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

     IX - quando necessário para atender aos interesses legítimos do controlador ou de terceiro, exceto no caso de prevalecerem direitos e liberdades fundamentais do titular que exijam a proteção dos dados pessoais; ou

     X - para a proteção do crédito, inclusive quanto ao disposto na legislação pertinente.

§ 1º (Revogado).
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

§ 2º (Revogado).
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

     § 3º O tratamento de dados pessoais cujo acesso é público deve considerar a finalidade, a boa-fé e o interesse público que justificaram sua disponibilização.

     § 4º É dispensada a exigência do consentimento previsto no

     caput

     deste artigo para os dados tornados manifestamente públicos pelo titular, resguardados os direitos do titular e os princípios previstos nesta Lei.

     § 5º O controlador que obteve o consentimento referido no inciso I do

     caput

     deste artigo que necessitar comunicar ou compartilhar dados pessoais com outros controladores deverá obter consentimento específico do titular para esse fim, ressalvadas as hipóteses de dispensa do consentimento previstas nesta Lei.

     § 6º A eventual dispensa da exigência do consentimento não desobriga os agentes de tratamento das demais obrigações previstas nesta Lei, especialmente da observância dos princípios gerais e da garantia dos direitos do titular.

§ 7º O tratamento posterior dos dados pessoais a que se referem os §§ 3º
e 4º deste artigo poderá ser realizado para novas finalidades, desde que
observados os propósitos legítimos e específicos para o novo tratamento e a
preservação dos direitos do titular, assim como os fundamentos e os
princípios previstos nesta Lei.
(Incluído pela Lei
nº 13.853, de 2019)

         Vigência
```

## Art. 11

```
Art. 11. O tratamento de dados pessoais sensíveis somente poderá ocorrer nas seguintes hipóteses:

     I - quando o titular ou seu responsável legal consentir, de forma específica e destacada, para finalidades específicas;

     II - sem fornecimento de consentimento do titular, nas hipóteses em que for indispensável para:

     a) cumprimento de obrigação legal ou regulatória pelo controlador;

     b) tratamento compartilhado de dados necessários à execução, pela administração pública, de políticas públicas previstas em leis ou regulamentos;

     c) realização de estudos por órgão de pesquisa, garantida, sempre que possível, a anonimização dos dados pessoais sensíveis;

     d) exercício regular de direitos, inclusive em contrato e em processo judicial, administrativo e arbitral, este último nos termos da

      Lei nº 9.307, de 23 de setembro de 1996 (Lei de Arbitragem)

     ;

     e) proteção da vida ou da incolumidade física do titular ou de terceiro;

f) tutela da saúde, exclusivamente, em procedimento realizado por
profissionais de saúde, serviços de saúde ou autoridade sanitária; ou
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

     g) garantia da prevenção à fraude e à segurança do titular, nos processos de identificação e autenticação de cadastro em sistemas eletrônicos, resguardados os direitos mencionados no art. 9º desta Lei e exceto no caso de prevalecerem direitos e liberdades fundamentais do titular que exijam a proteção dos dados pessoais.

     § 1º Aplica-se o disposto neste artigo a qualquer tratamento de dados pessoais que revele dados pessoais sensíveis e que possa causar dano ao titular, ressalvado o disposto em legislação específica.

     § 2º Nos casos de aplicação do disposto nas alíneas “a” e “b” do inciso II do

     caput

     deste artigo pelos órgãos e pelas entidades públicas, será dada publicidade à referida dispensa de consentimento, nos termos do inciso I do

     caput

     do art. 23 desta Lei.

     § 3º A comunicação ou o uso compartilhado de dados pessoais sensíveis entre controladores com objetivo de obter vantagem econômica poderá ser objeto de vedação ou de regulamentação por parte da autoridade nacional, ouvidos os órgãos setoriais do Poder Público, no âmbito de suas competências.

§ 4º É vedada a comunicação ou o uso compartilhado entre controladores
de dados pessoais sensíveis referentes à saúde com objetivo de obter
vantagem econômica, exceto nas hipóteses relativas a prestação de
serviços de saúde, de assistência farmacêutica e de assistência à saúde,
desde que observado o § 5º deste artigo, incluídos os serviços
auxiliares de diagnose e terapia, em benefício dos interesses dos
titulares de dados, e para permitir:
(Redação dada pela
Lei nº 13.853, de 2019)

         Vigência

I - a portabilidade de dados quando solicitada pelo titular; ou
(Incluído pela Lei
nº 13.853, de 2019)

         Vigência

II - as transações financeiras e administrativas resultantes do uso e da
prestação dos serviços de que trata este parágrafo.
(Incluído pela Lei
nº 13.853, de 2019)

         Vigência

§ 5º É vedado às operadoras de planos privados
de assistência à saúde o tratamento de dados de saúde para a prática de
seleção de riscos na contratação de qualquer modalidade, assim como na
contratação e exclusão de beneficiários.
(Incluído pela Lei
nº 13.853, de 2019)

         Vigência
```
