# DeepArch

DeepArch is a visual gallery of architecture diagrams for large language
models and open-source infrastructure. Each diagram includes an editable
Draw.io source file and, where available, an exported PNG for quick viewing on
GitHub.

## Preview

[![Transformer architecture](./Models/Transformer/transformer-transformer.drawio.png)](./Models/Transformer/README.md)

## Architecture gallery

### Large language models

[Arcee](./Models/Arcee/README.md) ·
[Cohere](./Models/Cohere/README.md) ·
[DeepSeek](./Models/DeepSeek/README.md) ·
[Gemma](./Models/Gemma/README.md) ·
[GLM](./Models/Glm/README.md) ·
[GPT-OSS](./Models/Gpt-oss/README.md) ·
[Granite](./Models/Granite/README.md) ·
[Grok](./Models/Grok/README.md) ·
[Hunyuan](./Models/Hunyuan/README.md) ·
[INTELLECT](./Models/Intellect/README.md) ·
[Kimi](./Models/Kimi/README.md) ·
[Laguna](./Models/Laguna/README.md) ·
[LFM](./Models/LFM/README.md) ·
[Ling](./Models/Ling/README.md) ·
[Llama](./Models/Llama/README.md) ·
[LongCat](./Models/LongCat/README.md) ·
[Mellum](./Models/Mellum/README.md) ·
[MiniMax](./Models/MiniMax/README.md) ·
[Mistral](./Models/Mistral/README.md) ·
[Nanbeige](./Models/Nanbeige/README.md) ·
[Nemotron](./Models/Nemotron/README.md) ·
[OLMo](./Models/Olmo/README.md) ·
[Phi](./Models/Phi/README.md) ·
[Qwen](./Models/Qwen/README.md) ·
[Sarvam](./Models/Sarvam/README.md) ·
[SmolLM](./Models/SmolLM/README.md) ·
[Step](./Models/Step/README.md) ·
[Transformer](./Models/Transformer/README.md) ·
[Vibe](./Models/Vibe/README.md) ·
[Xiaomi MiMo](./Models/Xiaomi/README.md) ·
[xLSTM](./Models/xLSTM/README.md) ·
[ZAYA](./Models/ZAYA/README.md)

### Open-source infrastructure

| Project | Diagrams |
| --- | --- |
| [Ceph](./Ceph/README.md) | Ceph and CephFS |
| [FUSE](./Fuse/README.md) | Filesystem in Userspace |
| [JuiceFS](./JuiceFS/README.md) | Architecture and I/O flow |

## Repository layout

```text
.
├── Models/<model-family>/   # LLM architecture diagrams
├── Ceph/                    # Ceph and CephFS
├── Fuse/                    # FUSE
└── JuiceFS/                 # JuiceFS
```

Diagram directories generally contain:

- `*.drawio` — editable source files.
- `*.drawio.png` or `*.png` — rendered images displayed by GitHub.
- `README.md` — a gallery page for the diagrams in that directory.

## View and edit

Open a gallery link above to view its rendered diagrams. To edit a diagram,
open the corresponding `.drawio` file in [diagrams.net](https://www.diagrams.net/)
or the Draw.io desktop application, then export the updated PNG alongside the
source file.

## Contributing

Contributions and corrections are welcome. When adding or updating a diagram:

1. Keep the editable `.drawio` source and exported PNG together.
2. Use a descriptive, consistent filename.
3. Add the rendered image to the nearest `README.md`.
4. Include references or implementation notes in the pull request when useful.

The diagrams are intended for learning and reference. Model implementations
can evolve, so verify details against the relevant source code or official
technical report.

## Reference

- [LLM Architecture Gallery by Sebastian Raschka](https://sebastianraschka.com/llm-architecture-gallery/)
