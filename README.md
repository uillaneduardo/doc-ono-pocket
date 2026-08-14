# Ono Pocket — Documentação

Repositório de referência para o **Game Design Document (GDD)**, a **World Bible do universo de Coluna** e a documentação técnica do **Ono Pocket**.

Este repositório existe para orientar desenvolvimento, narrativa, design de sistemas e decisões futuras sem misturar aquilo que faz parte do jogo atual com informações de bastidor do universo.

## Como interpretar a documentação

A documentação é dividida em três áreas principais:

- `lore/` — regras do universo, contexto histórico, sociedade, Onos e questões de worldbuilding.
- `game-design/` — experiência do jogador, mecânicas, progressão, recursos, mapa, base, narrativa presente e sistemas de gameplay.
- `tech/` — arquitetura e decisões técnicas de implementação.

Antes de adicionar ou alterar uma regra importante, consulte `lore/00_CANON_RULES.md` e o GDD.

## Escopo narrativo de Ono Pocket

Ono Pocket acompanha principalmente a perspectiva cotidiana de alguém que nasceu e vive em Coluna.

O foco narrativo imediato está em elementos presentes no dia a dia do jogador, como:

- sobrevivência;
- escassez e acesso a recursos;
- trabalho;
- deslocamento pela cidade;
- manutenção e desenvolvimento do abrigo;
- Onos modernos e o Vínculo entre humano e Ono;
- relações com NPCs;
- conhecimento e aprendizado;
- serviços e instituições;
- tensões sociais e conflitos que afetam a vida presente.

Informações de passado distante, segredos do mundo e explicações profundas da história de Coluna pertencem à World Bible e **não devem ser expostas automaticamente como conhecimento do jogador ou da população**.

Esses elementos podem ser revelados gradualmente conforme a narrativa exigir, permanecer apenas como fundamento do cenário ou ser explorados em outros projetos ambientados no mesmo universo.

> O passado sustenta o mundo. O presente sustenta Ono Pocket.

## Estrutura do repositório

### `game-design/`

- `GDD.md` — documento principal de game design; define visão, pilares, mecânicas e sistemas atualmente planejados.
- `00_GAMEPLAY_PRINCIPLES.md` — princípios gerais de gameplay.
- `01_RESOURCES_KNOWLEDGE_ACTIONS.md` — recursos, conhecimento, requisitos e transformação por ações.
- `02_MAP_BASE_TIME.md` — mapa, deslocamento, tempo, disponibilidade e progressão do abrigo.
- `03_ONO_OPERATION.md` — operação de Onos modernos, Vínculo, compatibilidade e operadores.
- `04_NARRATIVE_SCOPE.md` — define quais camadas da lore aparecem diretamente em Ono Pocket e quais permanecem como bastidor.

### `lore/`

- `00_CANON_RULES.md` — regras editoriais, terminologia e estados de cânone.
- `01_WORLD_TRUTH.md` — referência interna de worldbuilding e verdade de bastidor.
- `02_TIMELINE.md` — organização da sequência histórica conhecida pela documentação.
- `03_THE_COLUMN.md` — documentação sobre a Coluna e sua infraestrutura.
- `04_THE_EXODUS.md` — contexto histórico relacionado ao êxodo.
- `05_ANCIENT_ONOS.md` — referência sobre Onos da antiga era.
- `06_MODERN_ONOS.md` — origem e características dos Onos modernos.
- `07_THE_MYTH.md` — documentação sobre o Mito da Coluna e sua função social.
- `08_CURRENT_SOCIETY.md` — sociedade atual, cotidiano, escassez e contexto social.
- `09_FACTIONS.md` — princípios e espaço de desenvolvimento das facções.
- `10_ANCIENT_ONO.md` — referência de bastidor relacionada a um Ono da antiga era.
- `99_OPEN_QUESTIONS.md` — questões deliberadamente não resolvidas.

Os nomes dos arquivos de lore servem para organização interna. O conteúdo de bastidor não deve ser tratado como informação automaticamente conhecida durante o jogo.

### `tech/`

- `ARCHITECTURE.md` — direção técnica do projeto, stack, autoridade do servidor e princípios de implementação.

## Ordem recomendada de leitura para desenvolvimento

1. `README.md` — compreender a organização e o escopo.
2. `lore/00_CANON_RULES.md` — entender o que é cânone, provisório e aberto.
3. `game-design/GDD.md` — compreender a experiência e os sistemas planejados para Ono Pocket.
4. `game-design/04_NARRATIVE_SCOPE.md` — entender quais elementos narrativos pertencem ao jogo atual.
5. Consultar os documentos específicos de `game-design/`, `lore/` ou `tech/` conforme a funcionalidade em desenvolvimento.

## Estados editoriais

- **CANÔNICO** — decisão estabelecida e válida como referência.
- **PROVISÓRIO** — direção atual, ainda sujeita a revisão.
- **ABERTO** — ainda não definido; não deve ser preenchido automaticamente por ferramentas de IA.
- **DESCARTADO** — ideia removida do projeto.
- **EXEMPLO** — número, cenário ou hipótese usado apenas para ilustrar uma regra; não constitui cânone.

## Regras para desenvolvimento assistido por IA

Ao utilizar este repositório como contexto para uma IA:

1. Não inventar respostas para questões marcadas como abertas.
2. Não transformar exemplos ou sugestões em regras oficiais.
3. Não revelar ao jogador informações de bastidor apenas porque estão documentadas na World Bible.
4. Respeitar a terminologia oficial do projeto, incluindo **Vínculo** para a conexão operacional entre humano e Ono.
5. Priorizar `game-design/GDD.md` e `game-design/04_NARRATIVE_SCOPE.md` ao implementar conteúdo diretamente perceptível pelo jogador.
6. Apontar contradições entre documentos em vez de escolher silenciosamente uma versão.
7. Não adicionar frameworks, sistemas ou mecânicas sem necessidade ou sem compatibilidade com a documentação existente.

## Princípio de organização

A World Bible define o universo e suas regras.

O GDD define como Ono Pocket transforma parte desse universo em experiência jogável.

A documentação técnica define como essa experiência será implementada.
