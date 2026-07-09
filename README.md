<div align="center">

# Perming Gwee

### Creative Technologist & AI Consultant

**I build cinematic 3D & animated websites — and the production AI agents that run underneath them.**

</div>

---

A photographer who learned that a viewport is just another kind of camera, I run **[Ming Creatives](https://mingcreatives.com)** from Penang, Malaysia — building work where cinematic WebGL & motion engineering meets production-grade AI agents and automation. I hand-author the parts that demand taste: the shaders, the motion curves, the hard agent logic. Agents compress the boilerplate; the craft is still mine. In a Copilot era, craft matters more, not less.

> **Currently**
> - **Building** — a live Claude/GLM usage bridge ([`subscription-agent`](https://github.com/pmgwee/subscription-agent)) and a RAG knowledge assistant ([`Ai-Chatbot`](https://github.com/pmgwee/Ai-Chatbot))
> - **Exploring** — real-time 3D over live map data ([`real-penang`](https://github.com/pmgwee/real-penang)); vector search over personal corpora
> - **Open to** — creative-technology, cinematic-web, and AI-automation work

---

## Selected Work

**01 — [Ming Creatives](https://mingcreatives.com)**  ·  [code](https://github.com/pmgwee/ming-portfolio)

**Cinematic 3D, on the bleeding edge.** The studio's own brand site — a 3D-scrollytelling portfolio on Next.js 16 + React 19, built with GSAP, Framer Motion, and Lenis smooth scroll. This is where the photographer and the developer finally share a viewport.
`Next.js 16` · `React 19` · `GSAP` · `Framer Motion` · `Lenis` · `Tailwind v4`

**02 — [George Town Explorer](https://real-penang.vercel.app)**  ·  [code](https://github.com/pmgwee/real-penang)

**A playable 1:1 model of UNESCO George Town, built from live map data.** A gamified 3D walk (Three.js + GSAP + Vite) through Penang's heritage core, where every building footprint is fetched live from OpenStreetMap and extruded into 3D at its true GPS position — genuinely geographic, not hand-modeled. A custom PBR facade shader (triplanar plaster, per-building heritage tint, weathering), real Malaysian road markings, instanced street props, and landmarks placed at their true coordinates (Kuan Yin Temple, Jubilee Clock Tower, KOMTAR), finished with SSAO / bloom / color-grade. Where my photography obsession meets real-time graphics.
`Three.js` · `GSAP` · `Vite` · `WebGL shaders` · `Overpass / OSM` · `GLTF`

**03 — [Lando Norris Clone](https://lando-norris-clone-nine.vercel.app)**  ·  [code](https://github.com/pmgwee/lando-norris-clone)

**Pixel-faithful cinematic web.** A frame-for-frame reconstruction of [landonorris.com](https://landonorris.com) — after the original source was lost to a disk failure, this reuses the genuine Webflow design system and the real OFF+BRAND interaction bundle (GSAP, three.js, Rive), wrapped in a modern Vite + React + TypeScript shell. Verified parity: a sub-0.1 mean pixel diff versus production, zero console errors across every route.
`Vite` · `React 18` · `TypeScript` · `GSAP` · `three.js` · `Rive` · `Playwright`

**04 — [Subscription Agent](https://subscription-agent-five.vercel.app)**  ·  [code](https://github.com/pmgwee/subscription-agent)

**Production-grade AI-agent plumbing.** A full-stack Next.js 15 app that treats renewal math like it matters: a pure domain layer makes every charge date and monthly equivalent provably correct, with MYR-home multi-currency FX normalization. Its signature feature is a **live usage bridge** — each member runs one local script that reads their own Claude Pro and GLM usage and broadcasts it to a shared realtime dashboard, authenticated by per-user minted tokens. The bridge's smart 429 backoff (genuine errors retry fast; HTTP 429s climb a 60→300s ladder, honoring `retry-after` with a 60s floor) survived a real overnight lockout.
`Next.js 15` · `React 19` · `TypeScript` · `Supabase (RLS, Realtime)` · `Tailwind v4` · `Framer Motion`

**05 — [AI Knowledge Assistant](https://github.com/pmgwee/Ai-Chatbot)**  ·  RAG, end to end

**A retrieval-augmented study companion that grounds every answer in your own documents.** A RAG chatbot for interview prep and portfolio showcase — Python / FastAPI backend + Next.js 15 frontend. A LangGraph retrieve→generate agent chunks, embeds (a local `all-MiniLM-L6-v2` sentence-transformer — no API key needed), stores in Pinecone, and retrieves to produce cited, hallucination-resistant explanations. Built as a deliberate 8-phase climb — pipeline → chunking strategies → LangGraph agent → MCP / A2A tooling → production — to understand every layer of a real RAG system.
`Python` · `FastAPI` · `Next.js 15` · `LangChain` · `LangGraph` · `Pinecone` · `HuggingFace embeddings`

**06 — [Clone Website Plugin](https://github.com/pmgwee/clone-website-plugin)**  ·  *the one repo I've starred*

**An AI tool I built for my own workflow.** A Claude Code plugin that clones any website 1:1 — it reverse-engineers a site into structured **Design DNA** (colors, fonts, spacing, animation curves), reconstructs its WebGL and shader effects, then rebuilds it pixel-faithfully, behind a one-click `/clone-site` command.
Install: `claude plugin marketplace add pmgwee/clone-website-plugin`
`Claude Code Plugin` · `Skills` · `MCP` · `Design DNA`

---

<div align="center">

## Capabilities

**Cinematic web & motion** — Three.js · React Three Fiber · WebGL · GSAP · Framer Motion · Lenis · Blender · Figma
**AI agents & systems** — Python · RAG / vector search · LLM APIs (OpenAI, Anthropic) · Node.js · automation
**Product & platform** — TypeScript · React · Next.js · Tailwind CSS · Supabase · Postgres · Vercel
**Also fluent in** — Java · C++ · Dart / Flutter · Docker · Git · Photoshop · Illustrator

</div>

---

## Earlier work

University coursework, hackathon builds, and final-year projects from my BSc in Computer Science at USM — spanning web, mobile, blockchain, AI, and algorithms — are archived as read-only snapshots in a separate repo:

**→ [`pmgwee/past-projects`](https://github.com/pmgwee/past-projects)**

---

<div align="center">

## By the numbers

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=pmgwee&theme=tokyonight&show_icons=true&hide_border=true&count_private=true" alt="Perming's GitHub stats" /></p>
<p align="center"><img src="https://streak-stats.demolab.com/?user=pmgwee&theme=tokyonight&hide_border=true" alt="GitHub streak stats" /></p>
<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pmgwee&theme=tokyonight&hide_border=true&layout=compact" alt="Top languages" /></p>

![Profile views](https://komarev.com/ghpvc/?username=pmgwee&style=flat-square&color=7aa2f7&label=Profile+views)

</div>

---

<div align="center">

## Let's build something

Open to **creative-technology**, **cinematic-web**, and **AI-automation** work.

[![Email](https://img.shields.io/badge/perminggwee@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:perminggwee@gmail.com)
[![Portfolio](https://img.shields.io/badge/mingcreatives.com-7aa2f7?style=flat-square&logo=vercel&logoColor=white)](https://mingcreatives.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gweeperming-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gweeperming)
[![YouTube](https://img.shields.io/badge/YouTube-perminggwee-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/c/perminggwee)
[![LeetCode](https://img.shields.io/badge/LeetCode-pmgwee-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/pmgwee)

*Light, then motion, then the systems underneath.*

<sub>Built in Penang, Malaysia.</sub>

</div>
