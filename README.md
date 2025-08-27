# 🎵 AI Music Generator (Streamlit App)

Generate music and vocals from text prompts, lyrics, or random seeds using AI. This app runs **locally** and provides a user-friendly Streamlit interface to create, control, and download your musical creations.

---

## 🔧 Quick Start

### 1) Create & activate a virtual environment (recommended)

**Windows (PowerShell):**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**macOS / Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2) Install dependencies
> ⚠️ Make sure to install the correct **PyTorch** version for your system before installing the rest.

- **CPU-only:**
```bash
pip install torch --index-url https://download.pytorch.org/whl/cpu
```

- **NVIDIA GPU (CUDA 12.1):**
```bash
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

Then install the remaining dependencies:
```bash
pip install -r requirements.txt
```

### 3) Run the app
```bash
streamlit run app.py
```

On first run, the AI models will download, which may take a few minutes depending on your connection. Subsequent runs are faster thanks to caching.

---

## 🎛️ Features

- Generate **instrumental music** from text prompts.    
- Create **randomized melodies and beats**.  
- Control **duration, tempo, and genre**.  
- **Download output** as `.wav` or `.mp3`.  
- User-friendly **Streamlit web interface**, running fully locally.  

---

## 🔧 Libraries & Tools Used

- `streamlit` — interactive web app interface  
- `torch` — deep learning and model execution  
- `transformers` — for AI model handling (`AutoProcessor`, `MusicgenForConditionalGeneration`)  
- `numpy` & `soundfile` — audio processing and file handling  
- `matplotlib` & `io` — visualization and output handling  

---

## ❓ Usage Tips

- Keep text prompts concise for better musical output.  
- Experiment with different random seeds to generate unique melodies.  
- Adjust tempo, duration, and genre settings for variety.  
- Large or complex prompts may take longer to generate; breaking into smaller parts can help.  

---

## 🧱 What this app is (and isn’t)

- ✅ Local AI Music Generator with text → instrumental music.  
- ✅ Streamlit interface for easy experimentation.  
- ❌ It does not produce multi-track stems or full DAW arrangements.  
- ❌ It is not a professional music production tool — for mixing and mastering, use a DAW.  

---

## 📄 License

This template is provided "as is". Please ensure compliance with all AI model licenses and attribution requirements.

