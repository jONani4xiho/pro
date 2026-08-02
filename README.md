# QuakeCloud-burdie

An AI agent framework for JavaScript/TypeScript, organized as a pnpm monorepo.

## Features

- **Providers** — OpenAI (GPT-4, GPT-3.5), Anthropic (Claude 3.5 Sonnet), Google AI (Gemini 1.5). Swap at runtime.
- **Typed tools** — define functions with Zod schemas; parameters are validated and inferred automatically.
- **Streaming** — chunked, real-time responses on every provider.
- **Teams** — a lead agent spins up short-lived specialists for subtasks, then cleans them up.
- **MCP** — speaks the Model Context Protocol for consistent agent communication.

## Install

```bash
git clone https://github.com/user/QuakeCloud-burdie.git
cd QuakeCloud-burdie
pnpm install
```

MIT License.
