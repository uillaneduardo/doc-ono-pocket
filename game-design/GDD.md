# GDD — ONO POCKET

**Estado geral: PROVISÓRIO**

Este documento define a estrutura oficial de Game Design do Ono Pocket.

Ele deve ser lido em conjunto com a World Bible e as regras de cânone do repositório.

> World Bible define o que existe e por quê. GDD define o que o jogador pode fazer, como faz e quais decisões isso produz.

## Convenções de estado

### CANÔNICO
Regra de gameplay já decidida.

### PROVISÓRIO
Direção atual sujeita a balanceamento, refinamento ou redesign.

### ABERTO
Ainda precisa ser projetado.

### EXEMPLO
Valor, cenário ou número usado apenas para explicar uma mecânica. Não deve ser tratado como regra oficial.

---

# 1. VISÃO GERAL DO PROJETO

## 1.1 Conceito e identidade

**Estado: CANÔNICO**

Ono Pocket é um jogo web mobile-first, leve e predominantemente textual.

A interface deve usar texto, imagens, ícones, tipografia, painéis e mapas para apresentar informação com clareza.

O foco principal está em:

- sobrevivência;
- gerenciamento;
- exploração urbana;
- desenvolvimento de Onos;
- obtenção e transformação de recursos;
- aquisição de conhecimento;
- relações com NPCs;
- desenvolvimento gradual de autonomia.

O jogador vive como um cidadão comum de Coluna.

O jogo não precisa revelar toda a verdade histórica do universo.

## 1.2 Fantasia do jogador

**Estado: PROVISÓRIO FORTE**

O jogador começa com poucos recursos, um abrigo simples e acesso limitado à cidade.

Ele precisa sobreviver, trabalhar, obter recursos, cuidar de seu Ono, construir relações e adquirir conhecimento.

Ao longo do tempo conquista maior autonomia e novas possibilidades.

## 1.3 Core Loop

**Estado: PROVISÓRIO FORTE**

Objetivo
→ descobrir onde conseguir
→ deslocar-se
→ interagir
→ executar ação
→ consumir tempo e recursos
→ obter resultado
→ aumentar possibilidades
→ repetir

## 1.4 Pilares de gameplay

**Estado: CANÔNICO EM CONCEITO**

- Tempo é um recurso.
- Localização importa.
- Recursos existem fisicamente no mundo.
- Conhecimento desbloqueia possibilidades.
- NPCs são parte da progressão.
- O jogador deve decidir entre participação direta e delegação.
- A base representa autonomia.
- Onos modernos são ferramentas biológicas altamente adaptáveis.
- A progressão deve preferir novas capacidades a simples bônus numéricos.

---

# 2. MUNDO, TEMPO E ATIVIDADES

## 2.1 Disponibilidade

**Estado: CANÔNICO**

Jogador e Ono possuem disponibilidade separada.

Uma atividade pode ocupar:

- jogador;
- Ono;
- ambos;
- terceiros.

Enquanto ocupado, um participante não pode executar atividades incompatíveis.

## 2.2 Tempo

**Estado: CANÔNICO**

Ações significativas consomem tempo.

Exemplos:

- viajar;
- trabalhar;
- descansar;
- produzir;
- analisar;
- construir;
- reparar;
- negociar presencialmente;
- participar de missões.

Ações triviais de interface não precisam consumir tempo.

## 2.3 Sistema de ações

**Estado: PROVISÓRIO FORTE**

Toda ação pode possuir:

- contexto;
- participantes;
- duração;
- requisitos;
- custos;
- entradas;
- resultados;
- modificadores.

## 2.4 Mapa

**Estado: CANÔNICO EM CONCEITO**

O mapa representa locais físicos da cidade.

Cada local pode ter:

- estado de acesso;
- NPCs;
- serviços;
- atividades;
- requisitos;
- tempo de viagem.

Ao tocar em um ponto, o jogador recebe um resumo do que pode fazer naquele lugar.

## 2.5 Viagem

**Estado: CANÔNICO**

Viajar ocupa o jogador por um período.

A viagem conecta fisicamente as atividades do mundo.

O Ono pode ou não acompanhar o jogador, dependendo do contexto da atividade.

---

# 3. SISTEMA DE ONOS

## 3.1 Ono moderno

**Estado: CANÔNICO**

Onos modernos são organismos híbridos derivados dos Onos da antiga era.

Não possuem inteligência própria.

São recipientes cognitivamente vazios, embora possam executar comportamentos simples, condicionados ou automáticos.

Tarefas complexas dependem de orientação humana através do Vínculo.

## 3.2 Genética

**Estado: CANÔNICO EM CONCEITO**

A composição genética influencia:

- morfologia;
- resistência;
- metabolismo;
- capacidades físicas;
- adaptação ambiental;
- sistemas sensoriais;
- outras características biológicas.

Os Onos modernos surgiram da combinação de material genético Ono com DNA de outras criaturas devido à perda da infraestrutura e dos recursos necessários para reproduzir Onos da antiga era.

## 3.3 Vínculo

**Estado: CANÔNICO**

**Vínculo** é o termo oficial para a conexão entre humano e Ono utilizada para controlar, conduzir ou instruir o Ono de maneira assertiva.

O termo “link” não deve ser utilizado como sinônimo de Vínculo na documentação, narrativa ou interface.

O Vínculo depende de compatibilidade genética.

Maior compatibilidade pode melhorar:

- precisão;
- resposta;
- eficiência;
- desempenho operacional;
- sinergia entre operador e Ono.

## 3.4 Operação direta

**Estado: CANÔNICO EM CONCEITO**

Quando o jogador controla diretamente seu Ono através do Vínculo:

- jogador fica ocupado;
- Ono fica ocupado;
- compatibilidade genética influencia o desempenho;
- maior sinergia pode permitir melhor eficiência ou menor duração.

## 3.5 Operador contratado

**Estado: CANÔNICO EM CONCEITO**

Outro humano geneticamente compatível pode operar o Ono.

Isso libera o jogador para outra atividade, mas pode envolver:

- custo em créditos;
- desempenho inferior;
- maior consumo de recursos;
- desempenho dependente da compatibilidade do operador.

**EXEMPLO, NÃO CANÔNICO:** 80% de desempenho e +10% de consumo energético.

## 3.6 Linhagens

**Estado: CANÔNICO**

Famílias podem preservar linhagens Ono ao longo de gerações.

O reaproveitamento de material genético ajuda a manter:

- compatibilidade;
- características úteis;
- continuidade funcional.

É comum famílias reciclarem material genético de suas linhagens de Onos.

## 3.7 Obtenção e desenvolvimento

**Estado: ABERTO**

Ainda precisa ser definido:

- cultivo;
- tempo de formação;
- aquisição de novos Onos;
- regras de miscigenação;
- formas de evolução;
- limites genéticos;
- falhas e combinações inviáveis.

---

# 4. RECURSOS, CONHECIMENTO E ECONOMIA

## 4.1 Recursos

**Estado: CANÔNICO**

Recurso é qualquer coisa manipulável no mundo.

Pode representar:

- consumível;
- ferramenta;
- arma;
- documento;
- componente;
- material;
- amostra;
- alimento;
- equipamento;
- água;
- minério;
- célula de energia;
- anotações;
- blueprint.

## 4.2 Propriedades

**Estado: CANÔNICO EM CONCEITO**

Um recurso pode ser:

- comercializável ou não;
- empilhável ou único;
- conhecido ou não identificado;
- consumível ou persistente.

## 4.3 Transformação

**Estado: CANÔNICO EM CONCEITO**

Modelo conceitual:

**Recurso + ferramenta/equipamento + conhecimento + tempo → ação → resultado**

Recursos podem ser utilizados como entrada para gerar outros recursos.

## 4.4 Conhecimento

**Estado: CANÔNICO**

Conhecimento representa uma capacidade adquirida.

Não é apenas experiência numérica.

Pode desbloquear:

- ações;
- uso de equipamentos;
- construções;
- diagnósticos;
- opções de diálogo;
- interpretação de recursos;
- procedimentos;
- interações específicas com NPCs.

## 4.5 Aquisição de conhecimento

**Estado: CANÔNICO EM CONCEITO**

Pode vir de:

- NPCs;
- missões;
- blueprints;
- documentos;
- anotações;
- análise;
- experimentação;
- recursos consumidos;
- condições específicas alcançadas pelo jogador.

## 4.6 Créditos

**Estado: CANÔNICO EM CONCEITO**

Créditos são a moeda comum utilizada para serviços, trabalho, comércio, contratação e outros custos da sociedade.

## 4.7 Comércio

**Estado: CANÔNICO EM CONCEITO**

Parte do comércio exige presença física do jogador.

O comércio remoto pode ser uma capacidade conquistada posteriormente através de infraestrutura ou conhecimento.

## 4.8 OPP

**Estado: PROVISÓRIO**

Ono Pocket Points é uma moeda premium/intermediária em estudo.

Blockchain não faz parte do MVP.

---

# 5. ABRIGO, PROGRESSÃO E AUTONOMIA

## 5.1 Abrigo inicial

**Estado: CANÔNICO**

A base começa como um abrigo pequeno.

Funções iniciais:

- descanso;
- recuperação básica;
- armazenamento limitado.

## 5.2 Desenvolvimento

**Estado: CANÔNICO EM CONCEITO**

Novas capacidades podem exigir combinações de:

- recursos;
- conhecimento;
- ferramentas;
- favores;
- relações com NPCs;
- missões;
- descobertas.

## 5.3 Equipamentos

**Estado: PROVISÓRIO**

Possíveis instalações:

- bancada;
- estação de análise;
- armazenamento maior;
- gerador;
- incubadora;
- oficina;
- terminal.

A lista ainda não é definitiva.

## 5.4 Filosofia de progressão

**Estado: CANÔNICO**

Progressão deve significar novas capacidades.

Exemplo:

Antes:
- jogador depende de um NPC para realizar determinada ação.

Depois:
- aprende a técnica e obtém o equipamento adequado.

Resultado:
- pode realizar a ação sozinho.

## 5.5 Dependência e autonomia

**Estado: CANÔNICO**

A base reduz dependências externas, mas não substitui completamente a cidade.

A progressão pode ser resumida como:

**dependência → conhecimento → ferramenta → autonomia → especialização**

---

# 6. CONTEÚDO E NARRATIVA DE GAMEPLAY

## 6.1 Perspectiva

**Estado: CANÔNICO COMO DIREÇÃO NARRATIVA**

O jogador é inicialmente uma pessoa comum.

Suas preocupações imediatas são:

- sobreviver;
- trabalhar;
- obter água e recursos;
- cuidar de seu Ono;
- manter seu abrigo;
- lidar com a cidade e seus habitantes.

Ono Pocket não precisa ser uma narrativa sobre salvar o mundo.

## 6.2 NPCs

**Estado: CANÔNICO EM CONCEITO**

NPCs podem oferecer:

- trabalho;
- conhecimento;
- serviços;
- recursos;
- favores;
- acesso;
- missões;
- contatos.

NPCs não devem funcionar apenas como distribuidores de missões.

## 6.3 Missões

**Estado: PROVISÓRIO FORTE**

Missões podem alterar:

- relações;
- acesso a locais;
- conhecimento;
- recursos;
- possibilidades do jogador;
- desenvolvimento do Ono.

## 6.4 Lore

**Estado: CANÔNICO COMO DIREÇÃO NARRATIVA**

A lore profunda não precisa ser obrigatoriamente revelada.

Descobertas históricas devem preferencialmente acontecer de forma orgânica, como consequência de necessidades e ações do jogador.

A verdade objetiva do universo, aquilo que a sociedade acredita e aquilo que o jogador sabe são camadas distintas.

## 6.5 Facções e tensão social

**Estado: CANÔNICO EM CONCEITO / SISTEMA ABERTO**

A sociedade atual está entrando novamente em um período de forte tensão e novas facções estão surgindo.

Isso pode afetar:

- oportunidades;
- locais;
- relações;
- comércio;
- missões;
- acesso a recursos.

O sistema de facções ainda precisa ser projetado.

---

# 7. INTERFACE E SISTEMAS TÉCNICOS

## 7.1 UX

**Estado: CANÔNICO**

A interface deve ser:

- mobile-first;
- predominantemente textual;
- leve;
- legível;
- apoiada por cards, ícones, imagens e hierarquia tipográfica;
- orientada pelo mapa como uma das interfaces centrais.

A influência de CyberCode está na leveza e no foco em texto, não na densidade visual.

## 7.2 Telas iniciais possíveis

**Estado: PROVISÓRIO**

- Status/Início;
- Mapa;
- Local;
- Ono;
- Inventário;
- Abrigo/Base.

Locais como laboratório devem preferencialmente existir no mapa em vez de serem apenas menus abstratos.

## 7.3 Autoridade do servidor

**Estado: CANÔNICO TÉCNICO**

O cliente envia intenções.

O servidor valida:

- requisitos;
- tempo;
- custos;
- disponibilidade;
- inventário;
- resultados;
- recompensas.

O cliente nunca é autoridade sobre economia, timers ou geração de recursos.

## 7.4 Timers

**Estado: CANÔNICO TÉCNICO**

O servidor registra início e fim das atividades.

O cliente apenas representa visualmente o tempo restante.

## 7.5 Stack atual

**Estado: CANÔNICO COMO DIREÇÃO TÉCNICA ATUAL**

### Frontend
- React
- TypeScript
- Vite
- CSS próprio
- PWA

### Backend
- Node.js
- TypeScript
- Fastify
- Zod
- Drizzle

### Banco
- MariaDB

### Infraestrutura
- Docker
- Docker Compose
- GitHub
- Cloudflare Tunnel

## 7.6 Filosofia técnica

O projeto deve permanecer leve.

Evitar inicialmente tecnologias sem necessidade concreta, incluindo:

- Next.js;
- Redux;
- GraphQL;
- microserviços;
- Kubernetes;
- Redis;
- RabbitMQ;
- engines de jogos;
- renderização 3D no MVP;
- WebSockets indiscriminadamente.

---

# 8. QUESTÕES DE GAME DESIGN AINDA ABERTAS

- Como o jogador obtém seu primeiro Ono em detalhes?
- Como funciona o cultivo de novos Onos?
- Como funcionam as regras de miscigenação genética?
- Quais atributos e características de um Ono realmente importam?
- Como funciona energia do jogador e energia do Ono?
- Como funciona descanso?
- Como funciona exploração fora da zona segura?
- Como funcionam trabalhos e recompensas?
- Como funcionam falha, risco e consequências?
- Como funcionam treinamento e desenvolvimento dos Onos?
- Existirá combate? Em qual escala?
- Como será implementado o sistema de facções?
- Como relações com NPCs serão medidas ou representadas?
- Quais capacidades a base pode adquirir?
- Como funciona produção de recursos dentro da base?
- Como comércio entre jogadores funcionará no MVP?
- OPP fará parte da primeira versão ou será posterior?
- Qual é exatamente o primeiro arco jogável?

Este documento deve ser atualizado conforme decisões forem tomadas, sempre preservando a distinção entre CANÔNICO, PROVISÓRIO, ABERTO e EXEMPLO.
