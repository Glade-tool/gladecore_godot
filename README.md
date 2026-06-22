# GladeCore for Godot

**On-device conversational AI for your Godot game characters.** A local LLM for
chat, plus text-to-speech, speech-to-text, personalities & emotions, world lore,
RAG, and agentic actions — running on the player's machine, no server required
for the core. The same engine as the GladeCore **Unreal** and **Unity** SDKs.

Godot **4.4+** · **Windows** & **macOS** · [Get Pro at gladecore.com](https://www.gladecore.com/)

> The plugin is **free**. **Pro** features (RAG, actions, grammar, memory
> compression) unlock with a subscription key from
> [gladecore.com](https://www.gladecore.com/).

## Download & install

1. Download **`gladecore-1.0.zip`** from the [latest release](https://github.com/Glade-tool/gladecore_godot/releases/latest).
2. Unzip into your project so you have `res://addons/gladecore/`.
3. **Project → Project Settings → Plugins →** enable **GladeCore**.
4. Open the **GladeCore** dock → download a model (or drop a `.gguf` into `res://models/`).
5. Drag the **player** prefab + an **NPC** prefab into a scene, assign a personality `.tres`, and press Play.

Full documentation ships inside the download as `addons/gladecore/README.md`.

## Platforms

- **Windows** x86_64
- **macOS** universal (Apple Silicon + Intel)
- **Godot 4.4+**
- GPU acceleration: CUDA / Vulkan (Windows), Metal (macOS); CPU fallback otherwise

## Features

**Free**
- Local LLM chat with any GGUF model, streaming token output
- Per-NPC personality, emotions, persona/instructions, world lore
- Text-to-speech: Piper + Kokoro local voices (per-NPC, English + Mandarin); ElevenLabs with your own key
- Speech-to-text: Whisper push-to-talk
- Codeless drag-and-drop player + NPC prefabs, and a model-download dock
- NPC swapping with per-NPC context modes and memory persistence
- Cloud LLM backends (OpenAI-compatible, Anthropic) with your own key

**Pro** — subscription key
- RAG: grounded answers, strict grounding, refusal modes, output retrieval
- Agentic actions + inline action grammar
- GBNF structured output / grammar presets
- Chat memory compression

→ Activate Pro in **Project Settings → `glade_core/api_key`** (paste your key from
[gladecore.com](https://www.gladecore.com/); the dock then shows **License: Pro**).

## Models

Model weights are **not bundled** (they're large). Download them in-editor via the
**GladeCore** dock, or drop your own `.gguf` into `res://models/`.

## License

GladeCore is proprietary and free to use under its EULA (included in the download
as `EULA.md`). Bundled third-party components retain their own licenses (see
`Licenses/` in the download).

## Also available for

[Unreal Engine](https://www.gladecore.com/)
