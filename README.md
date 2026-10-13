# Michael Chen

AI software engineer at Epoch/ZergAI. CS graduate, UC Riverside (June 2026), with a minor in Entrepreneurship & Strategy.

## Open source

- **[mlx-audio](https://github.com/Blaizzy/mlx-audio/pull/859)** — fixed five divergences between the MLX iSTFTNet decoders (Kokoro, KittenTTS) and the PyTorch reference they were ported from, found by diffing every intermediate tensor across both stacks on identical inputs. Kokoro rendered 2.5 dB quiet (`istft` overlap-add normalized by Σw instead of Σw²), and the pitch/energy upsample path was misaligned one frame against its own shortcut (F0 relative RMSE 0.134 → 0.0000). Validated over 55 utterances against frozen fp32 reference audio with thresholds calibrated to the reference model's own render-to-render noise floor: MCD 7.29 → 4.09 dB, F0 RMSE 11.5 → 5.1 Hz. Merged upstream, with regression tests.

## Background

- **Epoch** — AI SWE Engineer: coding agents, terminal tooling, evaluation systems, multi-agent simulations.
- **MOBIVOLT LLC** — Software Engineer Intern: fuel-cell test automation, hardware simulation, firmware migration support.
- **AI at UCR** — Founder and President of UCR's first official AI organization (50+ members, 10+ workshops).
- **UC Riverside** — B.S. Computer Science, Dean's Honor List.

## Links

[Portfolio](https://mchen04.github.io) · [LinkedIn](https://www.linkedin.com/in/michael-luo-chen/)
