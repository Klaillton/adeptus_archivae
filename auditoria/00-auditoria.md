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

- 50 planetas: 8 conhecidos pelo Imperium e 42 ocultos.
- Os números de Guarda, Astartes e naves de guerra são projeção. Não estão implementados. Esperam autorização dos primarcas ou de Guilliman.
- O relatório omite comparação com os Custodes.
- Notas XII e XIII: manter o tom grimdark e a coesão com a lore atual de Warhammer.

`01-estrutura.md`, `02-lore.md` e `03-historia.md` aplicam essa precedência.

## Contradições

**Fundação.** Em dezembro de 2024 o Dante escolhe o período pós-Grande Cruzada, com raízes anteriores e sem força militar visível. Em 29 de abril de 2025 ele descreve a criação na primeira Cruzada, quando o Imperador passou a delegar papéis aos primarcas. O modelo calculou ~11.200 anos a partir de 800.M30. O compêndio não data a fundação. Fala em controle genético ao longo de ~10.000 anos. Status: **em aberto**. Os 11.200 anos são proposta do modelo.

**Lugar no Imperium.** Em abril de 2025: não subordinados ao Império, só ao Imperador e aos primarcas, estrutura à parte. Em fevereiro de 2025, no chat extra: operam fora do Imperium e, em público, dão ao Império o ganho político da subordinação. O compêndio, posterior, diz “ordem imperial”, “reconhecida mas vigiada”, lealdade “ao Imperador e à integridade do Império, acima das facções”. O mesmo compêndio esconde 42 dos 50 mundos. Status do rótulo: **travado** pelo compêndio. A autonomia acima das facções continua escrita nele. O detalhe de subordinação só pública continua **adotado** na história e não foi retirado.

**Escala.** Abril de 2025 explora 20 a 30 bilhões por mundo, 90 a 120 mundos e 2,5 a 3,2 trilhões de pessoas. O relatório travado fala em 50 planetas e 240 a 320 bilhões no total. Status da escala de abril: **substituído**. Os 240–320 bilhões e os 50 planetas estão **travados**.

**Força.** No chat extra e de novo em abril de 2025, o Dante fixa cerca de 50 mil Astartes conhecidos por fora, em autodefesa, e equipes externas de 3 Astartes mais suporte. O relatório travado projeta 5 a 8 milhões de Astartes e 5 a 8 bilhões de guarda, e o Dante exige que isso seja possibilidade, não efetivo. As duas frases convivem: 50 mil é a força conhecida; os milhões são plano. Status: **adotado** e **travado como projeção**, respectivamente.

**Hierarquia.** Três desenhos:

1. Janeiro de 2025: Magister Archivus, Magisters Primus, Operativus, Bellator, Investigatus, ordens de analistas, preservadores e protetores.
2. Abril de 2025: Magister Magnus, quatro Magisters (Militaris, Mentis, Technologus, Occulta) e quatro Ordos.
3. Compêndio: Iniciados, Archivistas, Custodians, Magisters, Conselho dos Archivae. À parte, a armadura escala Magister, Capitão, Battle-Brother, Guarda.

O desenho 3 é o que está no arquivo-base. Os desenhos 1 e 2 ficam **substituídos** como organograma oficial. O compêndio não diz como a escala da armadura encaixa na hierarquia civil. Isso fica **em aberto**.

**Naves.** A ficha de fevereiro de 2025 e o compêndio descrevem Lex Aeterna e Ultima Ratio Imperatoris como criações da facção. Em julho de 2025 o Dante diz que a nave nova é sigilosa e nunca foi usada até o presente da história. Em maio de 2026 ele diz que Lex e Ratio, para todos os efeitos, não existem, que ainda não foi decidido que eram necessárias, e que os primarcas sabem de uma Ratio e da capacidade dela. Status: a ficha de desenho está **travada** como conceito. A existência operacional está **em aberto**. A árvore de classes de maio de 2026 (Praetor-Archivum, Logos-Pattern, Vulkanis Bastion, Umbral Spear, Silent Lex, strike groups) é **proposta**. O modelo ofereceu reescrever isso como entrada oficial do compêndio. Essa reescrita não entrou no arquivo-base.

**Armadura.** No chat I a Terminator melhorada, com servo-crânios psíquicos, é o padrão de todos. A ficha posterior é o arquétipo de Elion, inspirado na Terminator, com servo-crânios de logística, defesa psíquica e análise. O compêndio escala essa armadura por patente. Status: Terminator psíquica universal **substituída**. Ficha de Elion e escalonamento **travados** como desenho. Quem já recebeu a armadura na história é cena (cerimônia fechada no chat VI).

**Recrutamento de Astartes.** O chat I trata o Archivae de combate como Iron Hand ou Salamander reforjado. O chat extra, do próprio Dante, muda isso: convite voluntário a Astartes caídos ou mutilados, só com permissão do mestre do capítulo, antes do Dreadnought. O compêndio mantém a projeção de gene-seed híbrido dos quatro patronos como plano não autorizado. Status: reforjo automático **substituído**. Convite voluntário **adotado**. Gene-seed híbrido em massa **travado como plano**.

**Nomes.** O Dante aponta, no chat I, perda de coesão de nomes. No chat V ele separa de novo: Rahn é o Alto Inquisidor traidor, não o Necron. O Senhor da Poeira é outra figura, a revisitar. Xar'os é o lorde Necron do pacto. Magister Caelus, do chat I, não é o administrador Kaelus da conspiração. Elion continua “Salamander ou Ultramarine” no compêndio. Status: grafia e identidade de cena **em cena**, com estes alertas. Não fechei o capítulo de origem do Elion.

**Poder de cena contra a nota grimdark.** Queda de Cadia reescrita, ROC, Termópilas, gênio e a campanha de Halcyon Reach empurram a facção para um patamar que o próprio compêndio manda tratar como potencial não autorizado, em tom grimdark. Ficam em história ou what-if. Não atualizam a ficha.

## Em aberto, sem terceira versão inventada

1. Data da fundação: pós-Cruzada (dezembro de 2024) ou durante a Cruzada, na delegação dos papéis (abril de 2025).
2. Lex Aeterna e Ultima Ratio: desenho travado, existência ainda não decidida em maio de 2026.
3. Encaixe entre a hierarquia Iniciados–Conselho e as patentes da armadura.

## Fora dos três arquivos

- Chat de 29 de junho de 2025. Não descreve a facção.
- Pedidos de imagem e o meta de gravar memória no ChatGPT.
- Perguntas de lore oficial de Warhammer que não viraram regra da facção: gótico e latim, lista de capítulos sucessores, Black Templars e Minotaurs em Optera, queda de Cadia no cânone, Vargard Obyron, Blood Ravens, Yvraine. O que gerou regra está anotado em `02-lore.md`.
- Os desejos pessoais do chat de março de 2026, antes de a cena virar um Archivae diante da entidade.
