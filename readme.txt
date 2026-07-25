# 🎨 Text-to-Image Generator using Stable Diffusion

Generate high-quality AI images from text prompts using the **Realistic Vision v6.0 HyperVAE** model. This project supports both **Text-to-Image (txt2img)** and **Image-to-Image (img2img)** generation through a user-friendly **Tkinter GUI**, running completely **offline** after setup.

---

## ✨ Features

- 🖼️ Text-to-Image Generation (txt2img)
- 🎨 Image-to-Image Generation (img2img)
- ⚡ Powered by Stable Diffusion + Realistic Vision v6.0
- 🖥️ Simple Tkinter Desktop GUI
- 📂 Automatic Output Folder Creation
- 💾 Download Generated Images
- 📋 Copy Output Path
- 🚀 GPU Acceleration (CUDA Supported)
- 💻 CPU Compatible (Generation will be slower)
- 🔒 Fully Offline After Model Download
- 🚫 No API Keys Required

---

## 📸 Application Preview

### Text-to-Image

Generate realistic AI images by simply entering a prompt.

### Image-to-Image

Upload an existing image and transform it using AI with your custom prompt.

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Diffusers
- Transformers
- Stable Diffusion
- Tkinter
- Pillow
- Safetensors

---

## 📁 Project Structure

```
Text-to-Image-Generator/
│
├── app.py
├── requirements.txt
├── runtime.txt
├── output/
├── static/
├── realisticVisionV60B1_v51HyperVAE.safetensors
└── README.md
```

---

# 🚀 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Text-to-Image-Generator.git

cd Text-to-Image-Generator
```

---

## 2️⃣ Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install --upgrade pip

pip install -r requirements.txt
```

If you don't have a requirements file, install manually:

```bash
pip install torch torchvision torchaudio
pip install diffusers transformers accelerate
pip install safetensors pillow flask
pip install omegaconf imageio
```

---

# 🤖 Download the AI Model

This project requires the **Realistic Vision v6.0 HyperVAE** model.

### Model Name

```
realisticVisionV60B1_v51HyperVAE.safetensors
```

### Download Source

https://civitai.com/models/4201/realistic-vision-v60

or

https://huggingface.co/

> **Note:** The model file is approximately **2–7 GB** and is **not included** in this repository due to GitHub's file size limitations.

After downloading, place the model file in the project root directory:

```
Text-to-Image-Generator/
│
├── app.py
├── realisticVisionV60B1_v51HyperVAE.safetensors
```

---

# ▶️ Run the Application

```bash
python app.py
```

A desktop GUI will open where you can:

- Enter a text prompt
- Upload a base image (optional)
- Generate AI images
- Save generated images
- Copy output path

---

# 💻 System Requirements

| Component | Requirement |
|-----------|-------------|
| OS | Windows / Linux / macOS |
| Python | 3.10+ |
| RAM | Minimum 8 GB (16 GB Recommended) |
| GPU | NVIDIA CUDA (Recommended) |
| Storage | 10 GB Free Space |

---

# 🖥️ GPU Support

The application automatically detects whether CUDA is available.

- ✅ NVIDIA GPU → Uses CUDA
- ✅ CPU → Works normally (generation will be slower)

---

# 📦 Dependencies

- torch
- torchvision
- diffusers
- transformers
- accelerate
- safetensors
- pillow
- flask
- imageio
- omegaconf

---

# 📂 Output

Generated images are automatically saved in:

```
output/
```

Each image is saved with a unique filename.

---

# ⚠️ Important Notes

- The AI model is **not included** in this repository.
- Download the model separately from CivitAI or Hugging Face.
- Image generation speed depends on your hardware.
- CPU generation may take several minutes per image.
- An NVIDIA GPU with CUDA is highly recommended for the best performance.

---

# 🛡️ Disclaimer

This project is intended for educational and research purposes.

The generated content depends entirely on the user-provided prompts. Please use the application responsibly and comply with all applicable laws and platform policies.

---

# ⭐ Future Improvements

- Multiple AI Model Support
- Negative Prompt Support
- Image Upscaling
- Batch Image Generation
- Prompt History
- Custom Resolution Selection
- Dark/Light Theme
- Image Metadata Viewer

---

# 🤝 Contributing

Contributions, feature requests, and bug reports are welcome.

Feel free to fork the repository and submit a pull request.

---

# 📜 License

This project is licensed under the MIT License.

---

# 🙌 Acknowledgements

- Stability AI
- Hugging Face 🤗
- Diffusers
- PyTorch
- CivitAI
- Realistic Vision Model Creators

---

## ⭐ If you found this project helpful, please consider giving it a Star on GitHub!