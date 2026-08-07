# Michael Chen

AI software engineer at Epoch, building autonomous coding-agent platforms, LLM evaluation harnesses, and multi-agent simulation infrastructure. CS graduate, UC Riverside (June 2026), with a minor in Entrepreneurship & Strategy.

## Work

- **Zerg / ZTC** — autonomous coding-agent platform and agentic terminal: parallel tool dispatch, background sub-agents, worktree-isolated batch execution, sandboxed multi-agent workflow runtime, MCP/provider routing, live web-mirror observability.
- **Forward-deployed engineering** — embedded AI platforms for enterprise customers: an org-management, procurement, and resource-planning platform with continual-validation harnesses (deterministic state, tool, artifact, browser, and visual oracles) for an aerospace manufacturer, and an AI procurement intake and approval portal with grounded vendor research, human-owned approvals, and RBAC/separation-of-duties controls for a publicly traded enterprise software company.
- **MOBIVOLT** — hardware-in-the-loop simulators, automated test systems, firmware migration (PIC32MZ to Harmony v3), and AI-assisted test and build automation for a $5M+ DOD-funded fuel-cell program: 250+ sensors, 5,000+ hours of testing.
- **PHiLIP** — [AMD University Program Award](https://www.hackster.io/contests/amd2023#category-1092)-winning human-in-the-loop image-generation platform on AMD ROCm with 2-second inference and PixArt-alpha fine-tuning.

## Open source

- **[mlx-audio](https://github.com/Blaizzy/mlx-audio/pull/859)** — fixed five divergences between the MLX iSTFTNet decoders (Kokoro, KittenTTS) and the PyTorch reference they were ported from, found by diffing every intermediate tensor across both stacks on identical inputs. Kokoro rendered 2.5 dB quiet (`istft` overlap-add normalized by Σw instead of Σw²), and the pitch/energy upsample path was misaligned one frame against its own shortcut (F0 relative RMSE 0.134 → 0.0000). Validated over 55 utterances against frozen fp32 reference audio with thresholds calibrated to the reference model's own render-to-render noise floor: MCD 7.29 → 4.09 dB, F0 RMSE 11.5 → 5.1 Hz. Merged upstream, with regression tests.
- **[Valence](https://github.com/jormyy/valence)** — patches to a friend's sports stream aggregator.

## Background

- **Epoch** — AI SWE Engineer: coding agents, terminal tooling, evaluation systems, multi-agent simulations.
- **MOBIVOLT LLC** — Software Engineer Intern: fuel-cell test automation, hardware simulation, firmware migration support.
- **AI at UCR** — Founder and President of UCR's first official AI organization (50+ members, 10+ workshops).
- **UC Riverside** — B.S. Computer Science, Dean's Honor List.

## Stack

**AI/ML:** LLM agents and tool use, RAG, MCP, LLM evaluation, multi-agent simulation, PyTorch, HuggingFace
**Languages:** Python, TypeScript, C++, C#, Go, Rust, SQL
**Systems:** Node.js, FastAPI, React, Next.js, PostgreSQL, Redis, Docker, Kubernetes, AWS, GCP

## Links

[Portfolio](https://mchen04.github.io) · [LinkedIn](https://www.linkedin.com/in/michael-luo-chen/)
