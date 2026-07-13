# Universal Activation Oracle — demo

Static gallery + live demo page for the Universal Activation Oracle (v24-dirfix): a single
Qwen3-1.7B + LoRA trunk that reads the internal activation of any LLM's response and answers,
calibrated, whether it exhibits a given behaviour — across architectures it was never trained on.

Live at: https://alexwortega.github.io/universal-ao/

- `index.html` — card gallery (client-side, from `examples.json`/`gallery_meta.json`) + an iframe
  into the live demo served from a research GPU box (`eva01`), running the same app as
  [`hf_space/universal-ao`](https://github.com/AlexWortega/qwen3-1p7b-nla/tree/main/hf_space/universal-ao)
  in the source repo.
- Source / training code: https://github.com/AlexWortega/qwen3-1p7b-nla
- Checkpoint: https://huggingface.co/AlexWortega/universal-nla-v24-dirfix
