https://deepspecmlx.llmtraining.dev

# DeepSpec
Apple‑Silicon‑optimised dashboard for speculative decoding built on MLX. Explore, benchmark, and visualise draft‑model acceleration with tools like Regeneration Console, Token Flow Visualiser, and Micro‑Benchmark Runner — bridging DeepSeek’s research with practical, interactive ML experimentation.

The DeepSpec MLX Dashboard is a modern, Apple‑Silicon‑optimised environment that reimagines speculative decoding through an interactive and visual interface. Built entirely on MLX, it transforms the foundational ideas introduced in DeepSeek’s original DeepSpec repository into a developer‑friendly experience that runs seamlessly on Mac hardware. Instead of requiring multi‑GPU setups or deep CUDA expertise, the dashboard makes speculative decoding accessible to researchers, developers, and students through a clean browser interface.

At its core, the dashboard provides a complete ecosystem for exploring, benchmarking, and visualising speculative decoding. The Regeneration Console allows users to compare draft and target model outputs interactively, revealing latency, acceptance, and verification patterns that explain how acceleration emerges. The Micro‑Benchmark Runner offers fine‑grained performance analytics, displaying latency trends, acceptance timelines, and draft‑versus‑target deltas through advanced charts. The Draft Model Playground enables live speculative decoding runs with adjustable parameters such as temperature and token limits, while the Token Flow Visualiser animates the decoding process in real time, showing how tokens are accepted, rejected, or regenerated step by step.

Complementing these interactive modules, the Target Cache Explorer provides a detailed view of cached samples, sequence lengths, and input IDs, helping users understand model caching behaviour. The Model Inspector lets users load and examine MLX or GGUF models—such as Qwen3‑0.6B—and view architecture details, runtime configuration, and device mode. Integrated GGUF Conversion Tools make it easy to convert MLX, PyTorch, or Hugging Face models into GGUF format for deployment, with quantization presets and direct download options. A built‑in Export JSON Utility allows users to extract runtime configurations, benchmark results, and regeneration data for external analysis.

Throughout the environment, a live System Status panel refreshes every two seconds, displaying CPU, memory, and GPU metrics alongside device information such as platform, architecture, and Python environment. This transparency ensures that users can monitor host performance as decoding runs unfold.

Every component of the DeepSpec MLX Dashboard is designed to bridge the gap between research and practical application. It turns speculative decoding from a low‑level algorithm into a hands‑on, visual experience—one that makes acceleration dynamics intuitive, measurable, and deeply informative. By combining the inspiration of DeepSeek’s original research with the flexibility of MLX and the efficiency of Apple Silicon, the dashboard stands as both a tribute to the pioneering work of DeepSpec and a forward‑looking tool for modern AI experimentation.

This MLX-based interactive version is derived from the concepts introduced in DeepSeek's original DeepSpec implementation: https://github.com/deepseek-ai/DeepSpec


