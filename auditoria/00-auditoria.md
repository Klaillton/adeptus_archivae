# Auditoria dos Adeptus Archivae

Leitura das 19 conversas em `Klaillton/adeptus_archivae` (`chatgpt-export/conversas/`, árvore `03e44d1`, outubro de 2026). O texto do modelo e o texto do Dante estão no mesmo fio. Esta auditoria separa o que cada um fixou.

Os arquivos locais `Documents\Adeptus Archivaes\MemóriaChatGPT.txt` e `Armadura, Naves.txt` repetem, quase palavra por palavra, o compêndio colado em 28 de outubro de 2025 e a ficha de armadura e naves. O `.txt` da memória já inclui as duas correções pedidas naquele chat: 50 planetas e força militar ainda não autorizada.

Nada disto foi commitado no GitHub.

## Como classificar

Cada fato tem uma camada e um status.

Camadas:

- **Estrutura** — instituição: cargos, mundos, população, força que existe, força que é só plano, armadura, naves.
- **Lore** — origem, missão, patronos, lealdade, relações, doutrina, limites.
- **História** — cenas, missões, campanhas, what-ifs.

Status:

| Status | Significado |
|---|---|
| Travado | O Dante escreveu ou colou como arquivo-base, ou corrigiu um número naquele texto. |
| Adotado | Ele escolheu, pediu para adotar, ou repetiu como fato da facção fora do compêndio. |
| Em cena | Ele conduziu o episódio. Vale como narrativa. Não vira ficha. |
| Substituído | Versão anterior que uma decisão posterior contradiz. |
| Proposta | Sugestão do modelo que ele não confirmou, ou oficina posterior que não entrou no arquivo-base. |
| What-if | Cenário hipotético. |
| Em aberto | Duas decisões dele discordam e nenhuma das duas foi retirada. |

Precedência, quando duas frases colidem: correção explícita posterior; texto colado como arquivo-base; decisão solta no chat; cena; proposta do modelo.

A prosa dos contos não foi transcrita. Os arcos saem dos turnos em que o Dante define, corrige ou pede para continuar.

## Mapa das conversas

| Data | Arquivo | O que é |
|---|---|---|
| 2024-12-31 | `adeptus-archivae-i` | Fundação da ideia, primeiras regras, contos avulsos. 287 turnos do Dante. |
| 2025-01-25 | `adeptus-archivae-história` | Imagem e um organograma que depois foi substituído. |
| 2025-01-30 | `adeptus-archivae-ii` | História. Ciclo dos enviados, missão Ecos do Passado. |
| 2025-02-07 | `adeptus-archivae-iii` | História. Declaração pública e missão hostil. |
| 2025-02-18 | `adeptus-archivae-iv` | História. Conspiração Rahn, Kaelus e Veydris; Consumidores; Xar'os. |
| 2025-02-23 | `conversa-extra-w40k-archivaes` | Consulta de Warhammer que gerou regras de recrutamento, escala de 50 mil Astartes e uso de tecnologia. |
| 2025-02-27 | `armadura-adeptus-archivae` | Ficha de armadura e naves. Vira estrutura. |
| 2025-03-05 | `adeptus-archivae-v` | História. Cela, Carcereiro, purificação. O próprio Dante separa Rahn de o Senhor da Poeira. |
| 2025-04-01 | `black-templars-vs-minotaurs` | Consulta de Warhammer e um hipotético curto. |
| 2025-04-29 | `linha-do-tempo` | Perfil da população dos planetas, mais oficina de escala e organograma. O perfil ficou. A escala e o organograma foram substituídos pelo compêndio. |
| 2025-06-29 | `e-personalidade` | Fora de escopo. Não entra no cânone. |
| 2025-07-01 | `adeptus-archivae-vi` | História. Fim das missões dos enviados. A nave nova é declarada sigilosa e ainda não usada. |
| 2025-07-15 | `adeptus-archivae-vii` | História. Política com o Império depois do retorno dos enviados. |
| 2025-10-28 | `salvar-informações-em-memória` | O compêndio é colado e tratado como arquivo-base. Meta de “salve na memória” fica de fora. |
| 2025-12-08 | `imperador-e-queda-de-cadia` | Consulta de Warhammer e what-if (Cadia reescrita, Termópilas). |
| 2026-03-25 | `desejos-e-distorsões-de-gênio` | Desejos pessoais ficam de fora. O trecho em que um Archivae enfrenta a entidade é what-if. |
| 2026-05-17 e 2026-05-18 | naves gigantescas e o branch | Oficina naval e a campanha Halcyon Reach. O Dante limita o que já existe. |
| 2026-10-18 | `comparar-motores-espaciais` | Regra técnica proposta, posterior ao compêndio. |

## O que prevalece

O arquivo-base é o **Compêndio Geral** de 28 de outubro de 2025, na forma do `MemóriaChatGPT.txt`. Dentro dele, o relatório a Guilliman já está na versão corrigida:

- 50 planetas: 8 conhecidos pelo Imperium e 42 ocultos. Correção de 1 de novembro de 2026: os 8 têm exposição controlada, os 42 são ainda mais avançados, e a população está na faixa de 20 a 30 bilhões por mundo. Toda a interação que o Imperium conhece aconteceu nos 8.
- Os números de Guarda, Astartes e naves de guerra são projeção. Não estão implementados. Esperam autorização dos primarcas ou de Guilliman.
- O relatório omite comparação com os Custodes.
- Notas XII e XIII: manter o tom grimdark e a coesão com a lore atual de Warhammer.
- Correção de 1 de novembro de 2026: a população dos planetas recebe características das sementes genéticas dos quatro primarcas por edição ao longo do tempo, com seleção das melhores e mais estáveis de cada uma. Não é a cirurgia dos Astartes. O cuidado com mutações e anomalias foi mantido.
- Correção de 1 de novembro de 2026, semente, travada a pedido do Dante. O hábito nasce solto, em cada frota, sem ordem: alguém guarda um quadro ou um diário. O primarca ouve, não se incomoda, e só então aparece um depósito de bordo e um padrão seu. Vulkan e Guilliman comentam, cada um no seu modo. A reunião dos quatro é que formaliza. Cabe depois de cada primarca ter frota; a conversa dos dois, depois de 837.M30; a reunião, depois de Lion.
- Correção de 1 de novembro de 2026, lugar no Imperium. Lealdade real ao Imperador, aos Primarcas e à Verdade Imperial. O Imperium atual não é digno do Imperador. Subordinação pública, fé mostrada à Eclesiarquia e abertura calibrada ao Mechanicus são diplomacia do retorno dos primarcas. Depois da queda, reclusão ao modo de Lion. Sem o último primarca ativo, ocultaram-se e, sem ordens novas, fizeram a base e a população.
- Correção de 1 de novembro de 2026, força, hierarquia, naves, armadura e recrutamento. A força fica nos 50 mil Astartes. A população resiste até eles chegarem. As três cartas da hierarquia passam a ser uma ordem, por trilhos. A reescrita naval de maio de 2026 entra. A ficha de armadura de Elion mantém-se. As forças militares ganham a linha Sororitas–Astra Militarum, em versão Archivae. O convite de Astartes abre-se a todos os capítulos leais, e cada um é recondicionado. Não há Dreadnought para todo o caído que não pode ser reconstruído. A oferta é tornar-se Archivae.
- Correção de 1 de novembro de 2026, formação e defesa. Toda a população faz pelo menos 50 anos de ensino e treino militar na capacidade máxima da ordem, e mais 25 anos de especialização escolhida pela própria pessoa, antes de exercer função. O nome dessa população é Filhos da Lumen Historiae. Os tipos de mundo de abril são especialização de cada planeta, e cada mundo mantém o mínimo para recomeçar isolado. O arquivo do conhecimento mais crítico não é replicado. Não há força de defesa planetária separada: a arma está difundida e o civil treinado é a resistência. O exercício do chat II permanece como o modelo o escreveu e o Dante aceitou: Voss traz o pedido dos generais, números iguais, equipamento padrão, a Guarda eliminada na prática. O detalhe acrescentado é o lado Archivae: população de uma cidade, ao acaso, não soldados escolhidos. Voss sabe. O relatório aos outros suaviza isso em forças iguais e diferença de treino.

`01-estrutura.md`, `02-lore.md` e `03-historia.md` aplicam essa precedência.

## Contradições

**Fundação.** Em dezembro de 2024 o Dante escolhe o pós-Grande Cruzada como o estado da ordem: raízes e organização já existem, sem força militar que pareça ameaça. Em abril de 2025 ele descreve a criação na Grande Cruzada, quando o Imperador passou a delegar papéis. Em 1 de novembro de 2026 ele fecha a forma. O hábito nasce solto em cada frota. O primarca formaliza só o seu, aos poucos. Vulkan e Guilliman conversam sem unir os modos. A reunião dos quatro é a formalização. O compêndio não data a fundação e fala em controle genético ao longo de ~10.000 anos. Os ~11.200 anos do modelo contavam desde 800.M30.

**Lugar no Imperium.** Em abril de 2025: não subordinados ao Império, só ao Imperador e aos primarcas, estrutura à parte. Em fevereiro de 2025, no chat extra: operam fora do Imperium e, em público, dão ao Império o ganho político da subordinação. O compêndio diz “ordem imperial”, “reconhecida mas vigiada”, lealdade “ao Imperador e à integridade do Império, acima das facções”, e esconde 42 dos 50 mundos. Em 1 de novembro de 2026 o Dante separa as camadas. A lealdade real é ao Imperador, aos Primarcas e à Verdade Imperial. O Imperium atual não é digno do Imperador, e não há submissão à política imperial. A subordinação pública, a fé mostrada à Eclesiarquia e a abertura calibrada ao Mechanicus são diplomacia surgida do retorno dos primarcas. Entre a queda do Imperador e esse retorno, a ordem seguiu o sigilo de Lion, ocultou-se com o desaparecimento do último primarca ativo, e sem ordens novas fez a base e a população. Status: **travado**. O rótulo do compêndio fica como face pública.

**Escala.** Abril de 2025: o Dante propõe 20 a 30 bilhões por mundo do tamanho da Terra. O modelo multiplica por 90 a 120 mundos e chega a 2,5 a 3,2 trilhões. Outubro de 2025 trava 50 planetas, 8 conhecidos e 42 ocultos, e o relatório escreve 240 a 320 bilhões no total. Em 1 de novembro de 2026 ele mantém os 50 e confirma a população na faixa que propôs, 20 a 30 bilhões por mundo. O total passa a 1,0 a 1,5 trilhão. Os 240 a 320 bilhões e os 90 a 120 mundos ficam **substituídos**. Os 8 têm exposição controlada, para não assustar o Imperium. Os 42 são ainda mais avançados. Toda a interação que o Imperium conhece aconteceu nos 8. Status: **travado**.

**Força.** No chat extra e de novo em abril de 2025, o Dante fixa cerca de 50 mil Astartes conhecidos por fora, e equipes externas de 3 Astartes mais suporte. O relatório projeta 5 a 8 milhões de Astartes e 5 a 8 bilhões de guarda, como possibilidade, não efetivo. Em 1 de novembro de 2026 ele confirma: a força fica nos 50 mil. A população é altamente capacitada e resiste até esses Astartes chegarem. Status: **travado**. A projeção do relatório continua plano.

**Hierarquia.** Três desenhos, agora uma ordem só, por trilhos. O grau é o do compêndio: Iniciados, Archivistas, Custodians, Magisters, Conselho. O topo que não combate é o Magister Magnus, também chamado Magister Archivus. As quatro cadeiras de abril são os Primus de janeiro: Militaris, Mentis, Technologus, Occulta. O campo é Operativus, Bellator e Investigatus. A escala Magister, Capitão, Battle-Brother e Guarda fica no trilho militar. O naval não é outra carta: casco no Fabricatum, emprego no Militaris, sigilo no Occulta. Status: **travado** em 1 de novembro de 2026.

**Naves.** A ficha de fevereiro de 2025 descreve o casco da Lex e da Ratio. Em maio de 2026 o Dante limita o que se sabe e descreve o paradeiro. Em 1 de novembro de 2026 manda aceitar a reescrita proposta: doutrina, famílias Praetor-Archivum, Logos-Pattern, Vulkanis Bastion, Umbral Spear e Silent Lex, e os Guardiões da Lex e da Ratio. Para todos os efeitos ninguém as viu. Os primarcas sabem de uma Ratio e da capacidade dela. Status: **travado**.

**Armadura.** No chat I a Terminator melhorada, com servo-crânios psíquicos, é o padrão de todos. A ficha posterior é o arquétipo de Elion. O Dante confirma essa ficha. As forças militares têm outra linha: versão Archivae da armadura das Sororitas, até armaduras semelhantes às da Astra Militarum, ambas muito superiores às contrapartes. O detalhe fica para depois. Status: arquétipo **travado**. Linha militar **travada** no âmbito, por explicar no funcionamento.

**Recrutamento de Astartes.** O chat I trata o Archivae de combate como Iron Hand ou Salamander reforjado. O chat extra muda isso: convite voluntário, com permissão do mestre, antes de enterrar o ferido num Dreadnought, e com teste de compatibilidade. Em 1 de novembro de 2026 o convite abre-se a todos os capítulos leais, e cada um é recondicionado. No mesmo dia o Dante precisa o caso: não há Dreadnought para todo o Astartes que cai e não pode ser reconstruído. A oferta é tornar-se Archivae. Gene-seed híbrido em massa continua plano. Status: **travado**.

**Nomes.** O Dante aponta, no chat I, perda de coesão de nomes. No chat V ele separa de novo: Rahn é o Alto Inquisidor traidor, não o Necron. O Senhor da Poeira é outra figura, a revisitar. Xar'os é o lorde Necron do pacto. Magister Caelus, do chat I, não é o administrador Kaelus da conspiração. Elion continua “Salamander ou Ultramarine” no compêndio. Status: grafia e identidade de cena **em cena**, com estes alertas. Não fechei o capítulo de origem do Elion.

**Poder de cena contra a nota grimdark.** Queda de Cadia reescrita, ROC, Termópilas, gênio e a campanha de Halcyon Reach empurram a facção para um patamar que o próprio compêndio manda tratar como potencial não autorizado, em tom grimdark. Ficam em história ou what-if. Não atualizam a ficha.

## Em aberto, sem terceira versão inventada

Os dois itens que estavam aqui fecharam em 1 de novembro de 2026. A hierarquia ficou numa ordem só, por trilhos. A reescrita naval foi aceite. A origem de capítulo do Elion continua sem escolha do compêndio, e está anotada em Nomes. O funcionamento interno da linha de armadura militar ficou para uma explicação posterior, a pedido do Dante.

## Fora dos três arquivos

- Chat de 29 de junho de 2025. Não descreve a facção.
- Pedidos de imagem e o meta de gravar memória no ChatGPT.
- Perguntas de lore oficial de Warhammer que não viraram regra da facção: gótico e latim, lista de capítulos sucessores, Black Templars e Minotaurs em Optera, queda de Cadia no cânone, Vargard Obyron, Blood Ravens, Yvraine. O que gerou regra está anotado em `02-lore.md`.
- Os desejos pessoais do chat de março de 2026, antes de a cena virar um Archivae diante da entidade.
