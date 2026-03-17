# Yashman Singh

CS @ Georgia Tech · Intelligence + FinTech · Currently @ **EXL**

I build things close to the metal — inference runtimes, AI pipelines, systems that have to work under pressure.

<br>

## 🔨 Recent Work

### [Aegis](https://github.com/Yashman-Singh/Aegis) &nbsp;—&nbsp; Local LLM Inference Scheduler
> Ollama has a VRAM management blind spot. Aegis fixes it.

A background runtime that sits between your apps and Ollama — priority job queuing, atomic VRAM reservation, forced model eviction, and a concurrent scheduler with a per-model `IDLE → LOADED → EVICTING` state machine. Built to prevent OOM crashes on Apple Silicon.

`Python` `FastAPI` `asyncio` `SQLite` `Next.js` `Metal API`

---

### [Hermes](https://github.com/Yashman-Singh/hermes-protocol) &nbsp;—&nbsp; Voice Dictation for macOS
> Whisper-fast dictation, fully on-device, no cloud.

Native macOS app with a sentence-boundary-aware ASR pipeline (Parakeet TDT on the Apple Neural Engine), optional local LLM refinement via Ollama, and universal text injection across native and Electron apps. Nothing leaves your machine.

`Swift` `AVAudioEngine` `FluidAudio` `Ollama` `Accessibility API`

<br>

## 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
