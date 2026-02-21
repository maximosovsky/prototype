# Architecture — FlappyFish-Clicker

## Overview

FlappyFish-Clicker — WebGL-кликер на Unity. Собранный билд для веба, загруженный на GitHub Pages.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Engine | Unity (WebGL export) |
| Runtime | Unity WebAssembly |

## Project Structure

```
├── FlapiFish/
│   ├── index.html           # Unity WebGL loader
│   ├── Build/               # Compiled WebGL binaries (WASM + data)
│   └── TemplateData/        # Unity template assets (icons, CSS)
├── pr/                      # Promo materials
└── LICENSE                  # MIT
```

## Key Concepts

- **Unity WebGL** — компилированный билд, исходников нет (только бинарники)
- **Сlicker mechanics** — геймплей основан на кликах/тапах
- **Static deploy** — чистый HTML + WebGL, не требует сервера
