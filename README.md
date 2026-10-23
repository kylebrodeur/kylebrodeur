<img src="https://kylebrodeur.xyz/brand/readme-headers/profile.png" alt="Kyle Brodeur: AI educator and systems builder, builder's notes on useful systems" width="100%">

# Kyle Brodeur

AI educator and systems builder at U of Digital. Builder's notes on
[useful systems](https://kylebrodeur.xyz), published weekly with the receipts
left in.

## The Modal Toolkit

A family of open-source GPU servers on Modal, plus one operator CLI that runs
the whole fleet. The runbooks are war stories, not checklists.

| Package | What it does |
| --- | --- |
| [modal-toolkit](https://github.com/kylebrodeur/modal-toolkit) | The operator CLI: init, pull, deploy, doctor, dashboard, cost |
| [modal-inference-server](https://github.com/kylebrodeur/modal-inference-server) | OpenAI-compatible GPU inference with hot-set routing |
| [modal-embedding-server](https://github.com/kylebrodeur/modal-embedding-server) | GPU embeddings with a sync protocol and model-selection evals |
| [modal-vision-server](https://github.com/kylebrodeur/modal-vision-server) | Classification and segmentation driven by a model card |
| [modal-finetune-server](https://github.com/kylebrodeur/modal-finetune-server) | LoRA fine-tune, merge to GGUF, honest eval gates |
| [modal-vault-server](https://github.com/kylebrodeur/modal-vault-server) | A hosted vault and MCP memory plane for agents |
| [modal-victoriametrics-server](https://github.com/kylebrodeur/modal-victoriametrics-server) | Single-node VictoriaMetrics, CPU only, scale to zero |
| [modal-shared-libs](https://github.com/kylebrodeur/modal-shared-libs) | Stdlib-first shared modules, vendored into every package |

There is a paid side too: a
[Modal Production Operator Kit](https://github.com/sponsors/kylebrodeur) and a
set of architecture services, for teams that want the work done with me
rather than handed to them.

## Agent tooling

Shared bash primitives for machine hygiene, an MCP server for capturing and
analyzing browser traffic, a model router that picks the right model tier per
turn, and a way to run a second coding agent as a persistent service.

- [pi-link](https://github.com/kylebrodeur/pi-link) - a local WebSocket network
  for coordinating Pi coding-agent terminals
- [pi-model-router](https://github.com/kylebrodeur/pi-model-router) - an
  intelligent per-turn model router

## Elsewhere

- [kylebrodeur.xyz](https://kylebrodeur.xyz) - the index of ongoing work
- [Builder's Notes](https://kylebrodeur.substack.com) - the writing
- [PlantFluent](https://plantfluent.com) - plant identification and a garden
  journal
- [Hugging Face](https://huggingface.co/kylebrodeur) ·
  [npm](https://www.npmjs.com/~kylebrodeur) ·
  [Ollama](https://ollama.com/kylebrodeur)

Building notes on useful systems, mostly. The receipts are in the repos.
