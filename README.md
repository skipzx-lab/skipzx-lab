# Sam Murdoch

AI and SaaS builder who does the analysis first. Most projects don't fail in the build; they fail because the wrong
thing got built. So before I write code I work out what should be built, and how we'll know it worked. Then I build it.

Australia based · working US and European hours · [burl.au](https://burl.au/)

## What I build

- **AI features that ship.** Retrieval pipelines, structured output, validation gates, and evaluation harnesses that
  replay real cases against candidate models.
- **SaaS MVPs end to end.** Auth, tenancy, quotas, admin surface, deployment.
- **Local inference** where data can't leave the building, including on hardware most people ignore.
- **Integrations and migrations**, including the ugly undocumented legacy kind.

## Open source

| Repo | What it is |
|---|---|
| [arcserve](https://github.com/skipzx-lab/arcserve) | OpenAI-compatible OpenVINO GenAI server for Intel Arc. Took Gemma 4 26B-A4B on one Arc Pro B60 from ~20 tok/s (vLLM) to ~60 tok/s single stream and ~130 tok/s across 4 streams, with working tool calls for coding agents. |
| [bandscribe](https://github.com/skipzx-lab/bandscribe) | Turns any song (Suno, Udio, anything) into parts you can play: chord sheet with timed lyrics, guitar and bass tabs in any tuning, drums, piano with a live play-along keyboard, melody and MIDI. Stem separation and transcription run locally on NVIDIA, AMD, Intel Arc, Apple or CPU. |
| [model-painter](https://github.com/skipzx-lab/model-painter) | Paints 3D-print models for multi-colour printing, by hand or by describing the look to Claude. Exports a 3MF that Elegoo, Orca and Bambu slicers open already painted. |
| [precision-5820-arc-b60-large-bar](https://github.com/skipzx-lab/precision-5820-arc-b60-large-bar) | Fix for "Resizable BAR not detected" on an Arc Pro B60 in a Dell Precision 5820: one hidden BIOS setting. |

## Recent work

- **Kindred**: an AI platform live in an Australian school, drafting individual learning plans. No identifiable data
  reaches the model, and every claim is citation validated before a human sees it.
- **Speccie**: a consumer AI research app, plus an autonomous ASX trading engine that has run its full daily loop
  unattended for six months on a live paper account.
- **A live aviation broadcast stream**: real-time overlay and multi-device control, under a second from operator to air.

## Stack

Python · TypeScript · SQL · FastAPI · Node · React · Next.js · Anthropic and OpenAI APIs · RAG · Postgres ·
Supabase · Firebase · Oracle Cloud · Vercel · OpenVINO · vLLM · llama.cpp · PyTorch · Three.js
