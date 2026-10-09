# Olá, sou o Filipe Borges 👋

Desenvolvedor **full-stack** com foco em **TypeScript, React e Supabase/Postgres**. Trabalho em produto SaaS multi-tenant em produção, do banco à interface, passando por automações com IA e WhatsApp.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-filipe--borges--devtech-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filipe-borges-devtech/)

## 🛠️ Stack

**Front-end:** React · TypeScript · Vite · Tailwind CSS
**Back-end:** Supabase · PostgreSQL (RLS, migrações) · Edge Functions em Deno · APIs REST
**Automação e IA:** agentes de atendimento com LLM · integrações de WhatsApp · fluxos de follow-up
**Engenharia:** Git (worktrees, Conventional Commits) · GitHub Actions · code review · testes automatizados

## 💼 Experiência

### Codex — Desenvolvedor full-stack
Atuo no **Nav**, a plataforma de CRM e atendimento da **PromoAção** (cruzeiros temáticos): CRM multi-tenant, atendimento por WhatsApp com agentes de IA, construtor de fluxos e automações de follow-up. Código privado do cliente. Alguns exemplos do que entreguei:

- **Automações de follow-up:** tela dedicada às réguas de follow-up, envio de mídia com miniatura e monitor de execuções de fluxos.
- **Segurança multi-tenant:** isolamento de dados por tenant com Row Level Security no Postgres e correções de papel/perfil de usuários que pertencem a mais de uma empresa.
- **Cadastro e autenticação:** prevenção e limpeza de perfis órfãos no fluxo de cadastro.
- **Ferramentas de time:** automação de trabalho paralelo com git worktrees, rodando também no CI.

Todo o ciclo passa por especificação, revisão de código, CI e validação em staging antes de produção.

## 📌 Projetos

Projetos que desenvolvi de ponta a ponta. O código é privado dos clientes; abaixo, o que cada um faz e como foi construído.

### 🚚 SaaS para transportadoras
Plataforma de gestão para o transporte rodoviário de cargas, em três partes:
- **Emissor de CT-e** (back-end): emissão e consulta do Conhecimento de Transporte Eletrônico junto à SEFAZ (MOC 4.00), com assinatura digital de XML por certificado A1, geração de DACTE em PDF com QR Code e rotinas agendadas. *TypeScript · Fastify · Clean Architecture/Hexagonal · Zod*
- **App do cliente** (front-end): telas de operação, relatórios e gráficos, exportação em PDF. *React · TypeScript · TanStack Query · shadcn/ui · Supabase*
- **Painel administrativo**: gestão de usuários em homologação e produção com papéis (admin/super admin), central de suporte com chamados e WhatsApp, dashboard de assinantes e receita, notificações in-app e push, e trilha de auditoria de toda ação. Roda em VPS própria atrás de HTTPS, com as chaves sensíveis só no servidor. *Fastify · React · Supabase*

### 🛂 Visa Intel — qualificação de vistos com agentes de IA
Plataforma que analisa casos de visto com agentes de IA: abertura e acompanhamento de casos, leitura de documentos (PDF, Word, Excel), coleta de informação na web e relatório de qualificação. Inclui um estúdio de agentes com base de conhecimento, versionamento, área de testes e integrações, além de painel de sistema com auditoria e monitoramento do motor. *React · TanStack Start · Supabase · Zustand · IA generativa*

### 🗂️ Agafy — gestão para agências
SaaS multi-tenant para agências gerenciarem projetos e clientes: painel com projetos, calendário, chat, equipe e notificações (com quadros arrastáveis); portal do cliente para revisar entregas, agendar e pedir upgrade de plano; e painel da plataforma para administrar agências, usuários e assinaturas. *React · TanStack Start/Router · Supabase (Postgres, Auth, RLS) · Tailwind*

### 🏗️ Dryenge — site institucional
Site institucional com páginas de apresentação, portfólio de obras com páginas por projeto e contato. *React · TanStack Start · Tailwind · Framer Motion · Cloudflare*
