# Arquitetura Técnica — Direção Atual

## Cliente

- React
- TypeScript
- Vite
- CSS próprio
- PWA

O MVP não depende de renderização 3D. A representação do Ono deve ser substituível e inicialmente pode ser textual ou estática.

## Backend

- Node.js
- TypeScript
- Fastify
- Zod
- Drizzle ORM

## Banco

- MariaDB

MariaDB é o banco principal do projeto.

## Infraestrutura

- Docker
- Docker Compose
- GitHub
- Cloudflare Tunnel

## Filosofia

Monólito modular e leve no MVP.

Evitar complexidade sem necessidade real, incluindo inicialmente Next.js, Redux, GraphQL, microserviços, Kubernetes, Redis, RabbitMQ, engines de jogos e bibliotecas pesadas de UI.

## Autoridade

O cliente envia intenções. O servidor valida e determina duração, custos, recompensas, inventário, economia e resultados.

Timers devem ser representados por timestamps de início e fim, com validação no servidor.