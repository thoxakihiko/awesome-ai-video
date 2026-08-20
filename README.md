# Awesome AI Video [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best AI text-to-video & image-to-video models, tools, and resources.

The space moves fast — this list focuses on what's actually usable today (mid-2026):
hosted models, open-source models you can self-host, the tooling around them, and
where to learn. Links go to official sources. Contributions welcome — see
[Contributing](#contributing).

**Legend:** 🔓 open-source / self-hostable · 💲 commercial / hosted · 🆓 has a free tier

## Contents

- [Hosted models](#hosted-models)
- [Open-source models](#open-source-models)
- [Tools & platforms](#tools--platforms)
- [Prompting tools & guides](#prompting-tools--guides)
- [Learning & communities](#learning--communities)
- [Contributing](#contributing)

## Hosted models

State-of-the-art commercial models you access via web app or API.

- [Seedance 2.0](https://dreamina.capcut.com/) 💲🆓 — ByteDance's narrative-driven model with native multi-shot generation and synchronized audio in a single pass. Access via [Dreamina](https://dreamina.capcut.com/) (international) or the [BytePlus API](https://www.byteplus.com/en/product/seedance).
- [Google Veo 3.1](https://deepmind.google/models/veo/) 💲 — Generates 48kHz synchronized dialogue, ambient sound, and music as part of the same diffusion pass. Usable through [Google Flow](https://labs.google/flow) and the Gemini app.
- [Runway Gen-4.5](https://runwayml.com/) 💲🆓 — The most precise control surface for directors: motion brushes, scene consistency, and the GWM-1 world model.
- [Kling 3.0](https://klingai.com/) 💲🆓 — Strong native audio and lip-sync across multiple languages, with a shared audio timeline across multi-shot sequences.
- [Luma Ray3](https://lumalabs.ai/dream-machine) 💲🆓 — The first AI video model with native 16-bit HDR output. Part of Dream Machine.
- [MiniMax Hailuo](https://hailuoai.video/) 💲🆓 — The 2026 value pick: quality between Pika and Runway at noticeably lower pricing.
- [Pika](https://pika.art/) 💲🆓 — Fast and accessible, great for short-form creative iteration and effects.
- [PixVerse](https://pixverse.ai/) 💲🆓 — Popular for stylized short-form and social video, with a generous free tier.
- [OpenAI Sora](https://openai.com/sora) 💲 — ⚠️ Being wound down: the web/app experience was discontinued April 26, 2026 and the API is scheduled to end September 24, 2026. Plan migrations to Veo, Kling, Runway, or Seedance.

## Open-source models

Models with public weights you can run yourself.

- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) 🔓 — Alibaba's Apache-2.0 model with a Mixture-of-Experts architecture (27B total / 14B active). The community favorite, with the largest LoRA ecosystem.
- [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) 🔓 — Tencent's 13B foundation model with a full open ecosystem: weights, multi-GPU inference, FP8, Diffusers and ComfyUI integrations.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) 🔓 — Lightricks' DiT model built for speed — generates 1216×704 video faster than real time.
- [Mochi 1](https://github.com/genmoai/models) 🔓 — Genmo's 10B Asymmetric Diffusion Transformer, released under Apache 2.0.
- [CogVideoX](https://github.com/THUDM/CogVideo) 🔓 — Tsinghua/Zhipu's open text- and image-to-video model combining a 3D VAE with an expert Transformer.

## Tools & platforms

Run, chain, and deploy the models above.

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) 🔓 — Node-based workflow UI; the de facto home for open-source video pipelines (Wan, Hunyuan, LTX, and more). See also [comfy.org](https://www.comfy.org/).
- [Wan2GP](https://github.com/deepbeepmeep/Wan2GP) 🔓 — "AI video for the GPU-poor" — runs Wan 2.1/2.2, Hunyuan, and LTX on low-VRAM GPUs.
- [fal.ai](https://fal.ai/) 💲 — Low-latency generative-media API hosting most major video models, including Seedance.
- [Replicate](https://replicate.com/) 💲 — Run thousands of models (many video) via a simple API, no GPU management.
- [SEELE TV](https://seele.tv/) 💲 — Cinematic AI video studio with scene consistency and shot-level camera control.
- [Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-video) 🔓🆓 — Weights, demos, and Spaces for nearly every open video model.

## Prompting tools & guides

Get better, more consistent output.

- [seedance-prompt-forge](https://github.com/thoxakihiko/seedance-prompt-forge) 🔓 — CLI + library that turns simple inputs into clean, structured prompts for Seedance, Kling, Runway, and Veo.
- [shotlist-forge](https://github.com/thoxakihiko/shotlist-forge) 🔓 — Expands one concept into a structured, shot-by-shot prompt sequence (built on seedance-prompt-forge).
- [Runway Help Center](https://help.runwayml.com/) — Official prompting and feature guides for Gen-4.x.
- [Kling AI](https://klingai.com/) — In-app prompt examples and templates.

## Learning & communities

- [r/aivideo](https://www.reddit.com/r/aivideo/) — General AI video generation community.
- [r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/) — Largest open-source generative-media community; heavy on ComfyUI video workflows.
- [r/comfyui](https://www.reddit.com/r/comfyui/) — Workflows, nodes, and troubleshooting for ComfyUI.
- [Artificial Analysis — Video](https://artificialanalysis.ai/text-to-video) — Independent leaderboard and benchmarks for video models.

## Contributing

Found something missing, or a broken link? Contributions are very welcome — please
read [CONTRIBUTING.md](CONTRIBUTING.md) and open a pull request. Keep entries
factual, link to official sources, and add one concise sentence on what makes the
entry worth knowing.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work. See [LICENSE](LICENSE).
