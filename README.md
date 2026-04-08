# Glyph APT Repository

Debian/Ubuntu apt repository for [Glyph](https://github.com/hamidfzm/glyph), a cross-platform markdown viewer.

## Setup

```bash
curl -fsSL https://hamidfzm.github.io/apt-repo/gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/glyph.gpg
echo "deb [signed-by=/usr/share/keyrings/glyph.gpg] https://hamidfzm.github.io/apt-repo stable main" | sudo tee /etc/apt/sources.list.d/glyph.list
sudo apt update
sudo apt install glyph
```

## Architectures

- amd64
- arm64

## About

This repository is automatically updated by the [Glyph release workflow](https://github.com/hamidfzm/glyph/blob/main/.github/workflows/release.yml).
