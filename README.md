# 🎤 RVC Voice Converter
The second stage of the AI Cover Pipeline. This notebook is dedicated to high-fidelity voice conversion using the **Applio (RVC v2)** engine.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zattyla/K-RVC-Colab/blob/main/RVC_Voice_Converter.ipynb)

## 💡 Why a Separate Notebook?
By separating the **Voice Conversion** from **Audio Separation**, we ensure:
- **Maximum Stability:** No more NumPy version conflicts.
- **VRAM Efficiency:** More GPU memory available for the RMVPE pitch extraction.
- **Fast Iteration:** Convert multiple vocals using the same loaded model without restarting.

## 🛠️ Features
- **Applio Engine:** The most stable RVC fork available.
- **RMVPE Support:** Best-in-class pitch detection for professional results.
- **Automated Setup:** Forced dependency management to prevent common Colab errors.
- **Easy Form UI:** Slider-based pitch control and text-based model selection.

## 📂 Folder Structure
- `/inputs`: Place your clean vocals (from UVR) here.
- `/outputs`: Find your AI-converted vocals here.
- `/Applio/logs`: Where your voice models are stored.

## 🚀 The 2-Step Workflow
1. Use the [UVR Elite Separator](LINK_PARA_SUA_COLAB_A) to get a clean vocal.
2. Use this **RVC Voice Converter** to transform the voice.
3. Mix them in any audio editor (Audacity, FL Studio, etc.).

## 🤝 Credits
- Powered by [Applio](https://github.com/IAHispano/Applio).
- RVC Technology by [Retrieval-based-Voice-Conversion](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI).

---
**Maintained by:** [nwletter](https://github.com/Zattyla)
