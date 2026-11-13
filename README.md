## Hi, I'm Aryav

I'm a university student who designs and builds AI products end to end, from the product idea and UX through to the backend, the voice pipeline and the desktop app.

I'm mostly interested in assistants that can actually do things for you, so remembering what matters, taking actions through tools, and being quick and natural to talk to.

I'm open to internships and graduate opportunities in software engineering and applied AI.

### Featured project: [Nova, a personal AI assistant](https://github.com/AryavKarthik/ai-assistant)

Nova is a personal assistant that feels like one brain across devices. It's a Next.js web app and an Electron desktop companion that share one Supabase backend.

- Long-term memory with hybrid retrieval (pgvector embeddings plus `pg_trgm` keyword search, fused with Reciprocal Rank Fusion)
- Tool use through Claude for reminders, Google Calendar, Gmail drafting and sending, YouTube, web search and scheduled agent loops
- Hands-free voice with an on-device "Hey Jarvis" wake word (ONNX), streaming speech-to-text, sentence-by-sentence text-to-speech and barge-in
- Desktop control on macOS and Windows behind a platform-adapter layer, with confirmation gates on any tool that runs code
- Performance work guided by per-turn timing logs, which cut wake-word CPU use by 300× and voice response time from 30 s to about 2 s

### Tech I work with

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?logo=electron&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?logo=googlecloud&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?logo=onnx&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)

The areas I spend most of my time on are LLM tool use and agents, retrieval and memory systems, real-time voice, full-stack web and desktop apps.

### What I'm working on now

- Making Nova's voice pipeline hold up in noisy rooms and handle interruptions better, and porting more of its desktop tools to Windows
- Trying newer LLMs with latency-tuned settings for real-time voice

### Get in touch

Open an issue on any of my repos or reach out through GitHub. I'm always happy to talk about AI products.
