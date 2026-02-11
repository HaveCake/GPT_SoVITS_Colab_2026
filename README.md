# GPT-SoVITS Colab (2026 Feb Updated) 🚀

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaveCake/GPT_SoVITS_Colab_2026/blob/main/GPT_SoVITS_Colab_2026.ipynb)

> **2026.02 Update:** Fixed dependencies, `fast_langdetect` missing directory error, and public URL generation issues.
> **2026年2月更新:** 修复了官方仓库在 Colab 上的依赖报错、目录缺失问题，并优化了一键启动流程。

## ✨ 特性 / Features

- ✅ **一键部署 (One-Click):** 基于 RVC-Boss 官方主分支，无需复杂配置。
- 🔧 **自动热修复 (Auto-Hotfix):** 自动处理 `fast_langdetect` 目录缺失导致的推理报错。
- 🌍 **稳定公网链接 (Public URL):** 通过自动修改 `config.py` 确保生成可用的 Gradio 链接。
- ⚡ **T4 GPU 支持:** 针对 Google Colab 免费 T4 环境优化。

## 🛠️ 使用方法 / Usage

1. 点击上方的 **"Open In Colab"** 徽章。
2. 在 Colab 中依次点击代码块左侧的 **播放按钮 (Play)**。
3. 等待最后一步输出 `Running on public URL: https://xxxx.gradio.live`。
4. 点击链接即可开始克隆声音！

## 📝 包含的修复 / Fixes Included

1. **System:** `apt-get install ffmpeg` (Audio processing requirement).
2. **Patch:** `mkdir -p .../fast_langdetect` (Fixes `FileNotFoundError`).
3. **Config:** Auto-set `is_share=True` in `config.py` for stable remote access.

---
*If this helps you, please verify my effort by giving a star! ⭐*
*如果这个项目帮到了你，请点个 Star 支持一下！⭐*
