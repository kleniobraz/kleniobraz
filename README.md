### Hi, I'm Klenio.

Audiovisual producer who started building the tools.
I design and run AI-powered systems for video production and marketing operations at [Grupo SB](https://github.com/seubone), in Natal, Brazil.

I build with AI coding agents every day. What I own is the part they don't:
the problem, the architecture, the constraints, production operations, and measuring whether the AI output is actually good.

---

#### What I'm building

**SB Clips** · *internal platform, private* · [case study →](https://github.com/kleniobraz/sb-clips-case-study)

Turns long podcasts into ready-to-publish vertical clips and full YouTube episodes.

```mermaid
flowchart LR
  A[Upload] --> B[FFmpeg audio]
  B --> C[Whisper on RunPod]
  C --> D[LLM scoring by audience fit]
  D --> E[YOLO reframe 9:16]
  E --> F[Burned-in captions]
  F --> G[S3]
```

`Python` `Flask` `Next.js` `n8n` `RunPod serverless GPU` `Claude API` `YOLO` `FFmpeg` `S3` `nginx` `pytest`
Includes evaluation scripts for reframing quality and caption review.

**MKT Hub** · *internal platform, private, team project*

Operations platform for the Grupo SB marketing team: tasks, delivery checklists, an AI reviewer for creative deliverables, and a REST API.

`TypeScript` `Next.js` `Drizzle` `Postgres` `Zod` `Docker` `GitHub Actions CI`

**Auto SFX Panel** · *public* · [repo →](https://github.com/kleniobraz/autosfxklenio)

Premiere Pro panel that places sound effects on timeline cuts automatically.

---

#### How I work

Spec first, then agents. Every system has a written contract (state machine, cost rules, what must never happen) that the agents follow.
Changes go through branches, pull requests and CI. I operate what I ship: VPS, deploys, incidents and fixes.

#### Currently learning

AI evaluation · Python fundamentals · software architecture · paid traffic analytics

---

[LinkedIn](https://www.linkedin.com/in/kleniobraz/) · [Instagram](https://www.instagram.com/kleniobraz/)
