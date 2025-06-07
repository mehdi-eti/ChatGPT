# ChatGPT

[ChatGPT.chat](https://regal-fenglisu-19f212.netlify.app)

[![Chat with this repo](https://regal-fenglisu-19f212.netlify.app/button/github.svg)](https://regal-fenglisu-19f212.netlify.app/?agent=github/ibelick/ChatGPT)

![ChatGPT screenshot](./public/cover_ChatGPT.webp)

## Features

- Multi-model support: OpenAI, Mistral, Claude, Gemini
- File uploads with context-aware answers
- Clean, responsive UI with light/dark themes
- Built with Tailwind, shadcn/ui, and prompt-kit
- Fully open-source and self-hostable
- Customizable: user system prompt, multiple layout options

## Agent Features (WIP)

- `@agent` mentions
- Early tool and MCP integration for agent workflows
- Foundation for more powerful, customizable agents (more coming soon)

## Installation

You can run ChatGPT locally in seconds, all you need is an OpenAI API key.

```bash
git clone https://github.com/ibelick/ChatGPT.git
cd ChatGPT
npm install
echo "OPENAI_API_KEY=your-key" > .env.local
npm run dev
```

## Built with

- [prompt-kit](https://prompt-kit.com/) — AI components
- [shadcn/ui](https://ui.shadcn.com) — core components
- [motion-primitives](https://motion-primitives.com) — animated components
- [vercel ai sdk](https://vercel.com/blog/introducing-the-vercel-ai-sdk) — model integration, AI features
- [supabase](https://supabase.com) — auth and storage

## License

Apache License 2.0
