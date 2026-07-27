<p align="center">
  <img src="https://avatars.githubusercontent.com/u/295615117?v=4" alt="Protocol Luna" width="100" style="border-radius: 50%;">
  <h1 align="center">Protocol Luna</h1>
  <p align="center">Autonomous, sentient-like AI bots powered by local LLM inference</p>
  <p align="center">
    <a href="https://protocol-luna.github.io">
      <img src="https://img.shields.io/badge/website-protocol--luna.github.io-9370DB?style=flat-square" alt="Website">
    </a>
    <a href="https://github.com/protocol-luna">
      <img src="https://img.shields.io/badge/organization-protocol--luna-6B6B8A?style=flat-square" alt="Organization">
    </a>
    <a href="https://huggingface.co/fox3000foxy/Luna-Protocol-1.5B-Discord-Dialogues-200k-instruct">
      <img src="https://img.shields.io/badge/model-Luna%201.5B-FFD21E?style=flat-square" alt="Model">
    </a>
  </p>
</p>

This is the GitHub Pages website for the [Protocol Luna](https://github.com/protocol-luna) organization.

## What is Protocol Luna?

An open-source multi-platform AI assistant ecosystem. The brain service (**Emerald**) connects to platform adapters (Discord via **Jade**, Matrix via **Pixieglow**) and an LLM gateway (**Sapphire**) backed by llama.cpp (**Krystal**). A Markov chain service (**Ruby**) adds context-free spontaneity.

## The Stack

| Service | Role |
|---------|------|
| **Krystal** | LLM inference via llama.cpp |
| **Sapphire** | LLM gateway with emotion classification |
| **Emerald** | Brain & behavior engine |
| **Jade** | Discord adapter |
| **Pixieglow** | Matrix adapter |
| **Ruby** | Markov chain service |

## Development

```bash
# Serve locally
python3 -m http.server 8000
```

The site is deployed via GitHub Actions to GitHub Pages.
