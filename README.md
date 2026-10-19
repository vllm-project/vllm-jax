<p align="center">
   <!-- This image will ONLY show up in GitHub's dark mode -->
  <img src="docs/assets/vllm_jax_dark_mode.png#gh-dark-mode-only" alt="vLLM JAX" style="width: 86%;">
    <!-- This image will ONLY show up in GitHub's light mode (and on other platforms) -->
  <img src="docs/assets/vllm_jax_light_mode.png#gh-light-mode-only" alt="vLLM JAX" style="width: 86%;">
</p>

<p align="center">
| <a href="https://docs.vllm.ai/projects/tpu/en/latest/"><b>Documentation</b></a> | <a href="https://blog.vllm.ai/"><b>Blog</b></a> | <a href="https://discuss.vllm.ai/c/hardware-support/google-tpu-support/27"><b>User Forum</b></a> | <a href="https://slack.vllm.ai"><b>Developer Slack</b></a>  (#sig-tpu) |
</p>

---

> [!IMPORTANT]
> **vLLM JAX is developed in [vllm-project/tpu-inference](https://github.com/vllm-project/tpu-inference).**
>
> This repository is the future home of the project. Until the move is complete, the code, issues, and pull requests live in tpu-inference. Please open issues and pull requests there.

<br>

## About

vLLM JAX (`vllm-jax`, formerly `tpu-inference`) is the vLLM hardware plugin for serving JAX models on TPU. It aims to:

- Push the limits of TPU hardware performance in open source.
- Keep vLLM's standard user experience, telemetry, and interface.

PyTorch-native TPU serving is a separate project, **[vllm-torchtpu](https://github.com/vllm-project/vllm-torchtpu)**. If you are serving PyTorch models on TPU, use that instead.

<br>

## Recommended models and features

The **[Recommended Models](https://docs.vllm.ai/projects/tpu/en/latest/recommended_models/)** and **[Feature Matrix](https://docs.vllm.ai/projects/tpu/en/latest/features/)** pages list the models and features validated through unit, integration, and performance testing. The full support matrix is in the [tpu-inference README](https://github.com/vllm-project/tpu-inference#tpu-support-matrix-dashboard).

<br>

## Get started

Get started with vLLM on TPUs by following the [quickstart guide](https://docs.vllm.ai/projects/tpu/en/latest/getting_started/quickstart/).

Visit our [documentation](https://docs.vllm.ai/projects/tpu/en/latest/) to learn more.

**Compatible TPU Generations**
- Recommended: v7x, v5e, v6e
- Experimental: v3, v4, v5p

<br>

## Recipes

- [v7x (Ironwood) Recipes](https://github.com/AI-Hypercomputer/tpu-recipes/tree/main/inference/ironwood/vLLM)
- [v6e (Trillium) Recipes](https://github.com/AI-Hypercomputer/tpu-recipes/tree/main/inference/trillium/vLLM)

<br>

## 🤝 Contribute

Contributions go to [vllm-project/tpu-inference](https://github.com/vllm-project/tpu-inference) until the move is complete:

- **🐞 Submit Bugs & Suggest Features:** Open a [new issue](https://github.com/vllm-project/tpu-inference/issues/new/choose).
- **👀 Provide Feedback on Pull Requests:** Review [open pull requests](https://github.com/vllm-project/tpu-inference/pulls).
- **📚 Improve Our Documentation:** Fix a typo, clarify a confusing section, or write a new recipe.

To contribute code, start with the **[Contributing Guide](https://github.com/vllm-project/tpu-inference/blob/main/CONTRIBUTING.md)** and the **[good first issues](https://github.com/vllm-project/tpu-inference/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)**.

<br>

## 💬&nbsp; Contact us

- For technical questions and feature requests, open a GitHub [Issue](https://github.com/vllm-project/tpu-inference/issues/new/choose) in tpu-inference
- For discussing with fellow users, use the [TPU support topic in the vLLM Forum](https://discuss.vllm.ai/c/hardware-support/google-tpu-support/27)
- For coordinating contributions and development, use the [Developer Slack](https://slack.vllm.ai) (#sig-tpu)
- For collaborations and partnerships, contact us at [vllm-tpu@google.com](mailto:vllm-tpu@google.com)
