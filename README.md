# unlocked uncensored-ai

**Android Native (Termux)**

Run the AI engine directly on your Android phone or tablet — no PC required!

**Requirements**

• Termux installed from F-Droid (NOT the Play     Store — it's outdated)
• 6 GB+ RAM Only the 2B model runs well on 6      GB devices.
• WiFi or mobile data for initial setup           (downloading engine + models)
• ARM64 processor (virtually all modern Android   phones/tablets)

**Setup**

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
cd thevoid-uncensored-AI
```
**Install Uncensored AI LLM**

```
bash Android/install.sh
```

**Launch Chat**

```
bash Android/start.sh
```
