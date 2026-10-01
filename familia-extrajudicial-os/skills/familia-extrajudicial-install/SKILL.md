---
name: familia-extrajudicial-install
description: "Esta skill deve ser usada pelo advogado dos interessados para instalar, configurar ou iniciar o familia-extrajudicial-os, escolher a pasta privada e preferências, ou atender /familia-extrajudicial-install. Configura o trabalho; não analisa cabimento nem recebe documentos do cliente."
---

# Instalação — advogado dos interessados

> **🖱️ Escolhas = botões:** usar **AskUserQuestion** para listas fechadas, com até quatro opções por pergunta; dividir listas maiores. Nome, OAB, cidade, e-mail e caminho são texto livre. Se a ferramenta estiver indisponível, explicar a limitação e oferecer escolhas numeradas, sem fingir botões.

## Passo 0 — Prepare a sua fábrica jurídica

Orientar a criação ou escolha de uma pasta privada **CoWork OS**, antes da configuração: Windows `C:\CoWork OS`; Mac, pasta `CoWork OS` na pasta do usuário, pelo Finder. Pedir ao operador para selecionar essa pasta no Cowork e conceder acesso. Não prometer acesso que não foi concedido nem iniciar varredura de pastas. Não mover documentos preexistentes.

Verificar o caminho informado: precisa ficar fora do source do plugin e de repositórios compartilhados. Se apontar para o source ou faltar autorização de acesso, interromper a gravação e orientar a escolha de outra pasta. Manter cada cliente e matéria separados na pasta privada; nunca persistir perfis, autos ou exemplos identificáveis no plugin.

## Configurar, uma pergunta por vez

1. Pasta privada: colher o caminho em texto livre e confirmar acesso. A instalação não pede documentos de caso.
2. Perfil: oferecer **Advogado dos interessados**, **Defensor público**, **Outro papel**, **Ainda não definido**. Nos dois últimos, esclarecer o papel antes do fluxo jurídico; atuação como delegatário fica fora deste produto. Nome/OAB são opcionais, em texto livre; não inventar credencial.
3. Preferência inicial: **Divórcio**, **União estável**, **Inventário**, **Ainda não sei**. Preferência não certifica cobertura jurídica de um caso.
4. Modalidade preferida: **Presencial**, **Eletrônica**, **A definir**. Eletrônica exige conferência posterior específica; não conectar nem operar plataforma notarial.
5. Tom: **Objetivo**, **Didático**, **Técnico**. Revisão R1→R4 permanece ligada em qualquer tom; não oferecer botão para desligar travas.
6. Se útil, colher UF de preferência em texto livre ou em grupos com até quatro botões. UF do perfil não substitui as UFs de cada caso.

Mostrar resumo da configuração e confirmar com botões **Confirmar**, **Corrigir**, **Não salvar**. Se confirmado e permitido, salvar apenas o perfil necessário em arquivo de configuração na pasta privada escolhida, sem sobrescrever configuração existente; ler e reconciliar antes. Sem acesso, entregar o resumo na conversa e indicar persistência pendente. Não criar arquivo vazio para simular sucesso.

## Primeiro uso

Orientar: invocar `/familia-extrajudicial-master` e informar ato, interessado assistido, fatos, partes, datas, fase, objetivo, UFs e modalidade; fornecer todos os documentos pertinentes dentro da matéria privada. Não pedir dossiê na instalação nem certificar revisão de caso não recebido.

Verificar a presença local do master, guard, validador e Suprema Corte antes de afirmar disponibilidade. Cada um é controle por instrução (**Guidance only**), não enforcement por hook. Não presumir guard global instalado. Ausência de alguma skill é dependência pendente, nunca autorização para contornar revisão.

Fechar com configuração confirmada ou pendência, caminho de persistência efetivo e próxima ação. Suporte: **luis@sbroggio.io**. Não prometer publicação, sincronização ou URL de marketplace não confirmadas. Instalação não emite selo normativo e não declara cabimento.
