# Alade YESSOUFOU

Software engineer building developer tools and programming languages. I work mostly in
Node.js, and I'm currently learning Go.

## Projects

- **[uptime-monitor](https://github.com/devalade/uptime-monitor)**: An edge-native uptime
  monitor built with Remix 3 on Cloudflare Workers. HTTP, TCP, DNS and heartbeat checks swept
  by a per-minute cron, with multi-region re-checks from Durable Objects before an outage is
  declared. Ships a public status page with 90-day uptime bars, SVG badges, an RSS feed, a
  REST API with Prometheus metrics, and an MCP server so agents can list monitors and trigger
  checks.

- **[shipnode](https://github.com/devalade/shipnode)**: A CLI to deploy Node.js apps to a
  single VPS with zero-downtime releases, PM2, and Caddy. No Docker, no Kubernetes. The
  interesting part is the fluent config builder and Capistrano-style release symlinks with
  instant rollback, plus built-in SSH hardening and Cloudflare Tunnel support.

- **[AlgoLang](https://github.com/devalade/algo)**: An educational programming language with
  intuitive French syntax that compiles to JavaScript. A from-scratch lexer to parser to codegen
  pipeline, with a pedagogical mode that annotates the generated JS so learners can see how
  their code maps to JavaScript.

- **[crudify](https://github.com/devalade/crudify)**: A Laravel package that scaffolds full CRUD
  from a single command. It generates models, migrations, policies, Livewire v4 / Volt pages,
  factories, and seeders, with relationships, soft deletes, file uploads, and searchable fields.

- **[adam](https://github.com/ZeL4bs/adam)**: A filesystem-first framework for durable AI agents
  that runs as a long-lived Node process on a self-hosted VPS. An agent is authored as a directory
  of instructions, tools, skills, and schedules, then built and deployed (often via shipnode).

- **[reflection](https://github.com/devalade/reflection-class)**: A zero-dependency TypeScript
  library for runtime introspection of JavaScript classes and objects, inspired by PHP's
  Reflection. Discover properties and methods with descriptors, invoke members dynamically, and
  optionally read decorator metadata, aimed at plugin systems, serializers, and lightweight DI.

- **[better-primitives](https://github.com/devalade/better-primitives)**: Effect-shaped async
  primitives for TypeScript built on Promise, AbortSignal, and better-result, with no Effect
  runtime. It models a lazy Task with an explicit typed-failure channel, plus typed streams,
  resources, scopes, and structured concurrency.

## AdonisJS

Published packages and work built around AdonisJS 7.

- **[adonis-bachs](https://github.com/devalade/adonis-bachs)**: Bachs payments for AdonisJS —
  hosted checkout, subscriptions, refunds, payouts and signed webhooks, typed end to end with the
  whole API surface generated from Bachs' own OpenAPI document.

- **[adonis-chariow](https://github.com/devalade/adonis-chariow)**: Sell through Chariow from an
  AdonisJS app: start a checkout, receive signed Pulse webhooks, gate a SaaS on a license key,
  and run subscriptions on top of licences. Two runtime dependencies: `zod` and `better-result`.

- **[adonis-admin](https://github.com/devalade/adonis-admin)**: A Filament-inspired admin panel for
  AdonisJS 7 rendered with Edge templates — no Inertia, no React, no runtime dependencies.

- **[observe-adonisjs](https://github.com/devalade/observe-adonisjs)**: A clone of the NestJS
  Observe product (landing page plus dashboard UI) built as a pnpm and Turborepo monorepo with a
  single AdonisJS 7 + Inertia React app on a shadcn-based design system.

## Products

- **[onpair.dev](https://onpair.dev)**: A GitHub App that reviews every pull request for the
  documentation it leaves behind — renamed environment variables, changed routes, stale config
  keys, altered public exports — and reports back as a check run before the drift ships.
  Deterministic contract analysis first, an optional AI doc-drift pass on top.

- **[freestack](https://freestack.devalade.me)**: A suite of around twenty small bilingual
  (FR/EN) web tools — biolink, waitlist, feedback, status page, forms, polls, paste, split bill,
  bookmarks, countdown and more. TanStack Start, PocketBase and DaisyUI, deployed with shipnode.

- **vawu.chat**: A front door to the open-source models.

## Contributions

- **[trivule](https://github.com/jsbenin/trivule)**: A TypeScript library for form validation in
  plain HTML or JavaScript, with real-time, declarative rules. Part of the JSBenin community.

## Writing

- [Diagnosing a flash of unstyled content in TanStack Start production](https://devalade.me/blog/diagnosing-a-flash-of-unstyled-content-in-tanstack-start-production/)
- [Beginner guide: deploy a Node.js app with shipnode](https://devalade.me/blog/beginner-guide-how-to-deploy-a-nodejs-app-with-shipnode/)
- [Durable Objects 101: sequential state on the edge](https://devalade.me/blog/durable-objects-101/)

## Contact

- Email: github@devalade.me
- Site: https://devalade.me