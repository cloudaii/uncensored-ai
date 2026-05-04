# unlocked uncensored-ai

USB-Uncensored-LLM is a fully air-gapped, zero-dependency, plug-and-play Local AI environment designed to run seamlessly from your local hard drive or a portable USB/SSD. It bypasses complex installations natively executing large language models directly on your hardware with no internet required.

With a unified architecture, you can initialize your AI models once and choose to keep them on your system or carry them with you across Windows, macOS, and Linux PCs.

# Features 

• **Zero Dependency Setup**: Ships with portable Python and isolated engine binaries. No system permissions, registry edits, or package managers required.


• **Cross-Platform Interoperability**: Uses a intelligent Shared volume system — download your 5GB+ AI models once, and use them natively on Windows, macOS, and Linux without duplication.


• **Censorship Free**: Integrates cutting-edge ablative and heretic fine-tuned models for completely unfiltered interactions.


• **Network Proxied UI**: The custom Python HTTP server instantly serves a blazing-fast dark mode UI. You can access the AI from your phone or tablet on the same WiFi network without complex CORS configuration.


• **Hardware Accelerated**: Uses a custom-compiled Ollama engine under the hood, natively capitalizing on AVX CPU instructions, NVIDIA CUDA, or Apple Metal GPU accelerators dynamically when plugged into different host machines.

# Android Native (Termux)

Run the AI engine directly on your Android phone or tablet — no PC required!

# Requirements

• Termux installed from F-Droid (NOT the Play     Store — it's outdated)

• 6 GB+ RAM Only the 2B model runs well on 6      GB devices.

• WiFi or mobile data for initial setup           (downloading engine + models)

• ARM64 processor (virtually all modern Android   phones/tablets)

# Setup

1. Copy the USB-Uncensored-LLM folder to your      Android device (via USB OTG, file transfer,     or git clone)
   
2. Open Termux and navigate to the project         folder
   
3. Run: bash Android/install.sh
   
4. Select your model (Gemma 2 2B recommended       for most Android devices)
  
5. Wait for downloads to complete — keep Termux    in the foreground!

**clone repo**
```
git clone https://github.com/cloudaii/uncensored-ai.git
```
**Nevigate to cloned repo**

```
cd uncensored-ai
```
**Install Uncensored AI LLM**

```
bash Android/install.sh
```

**Launch Chat**

```
bash Android/start.sh
```
