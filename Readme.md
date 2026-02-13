

```markdown
# Local Voice Cloning with Qwen3-TTS

This project implements a local, high-fidelity voice cloning pipeline using the **Qwen3-TTS** model architecture. It is designed to run efficiently on local hardware using PyTorch.

## 🚀 Features
* **Zero-Shot Voice Cloning:** Clone voices using short reference audio samples.
* **Local Execution:** Runs entirely on your machine for privacy and speed.
* **Jupyter Workflow:** Easy-to-follow experimentation via `new.ipynb`.

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/Ravikant-jain/Local_Voice_cloning.git](https://github.com/Ravikant-jain/Local_Voice_cloning.git)
cd Local_Voice_cloning

```

### 2. Download the Model Weights

The model weights are large and are excluded from this repository. You **must** download them manually from Hugging Face into the project root:

```bash
git clone [https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base)

```

### 3. Setup Environment

Ensure you have your virtual environment active, then install the dependencies:

```bash
pip install -r requirements.txt

```

---

## 📂 Project Structure

* `new.ipynb`: The main notebook for running the TTS and voice cloning logic.
* `Qwen3-TTS-12Hz-0.6B-Base/`: Directory for model weights (ignored by Git).
* `inputs/`: Place your reference `.wav` files here.
* `outputs/`: Generated voice clones will be saved here.
* `requirements.txt`: Python dependencies.

---

## 📋 Usage

1. Place a target voice sample (e.g., `target_voice.wav`) in the `inputs/` folder.
2. Open `new.ipynb` in VS Code or Jupyter.
3. Run the cells to load the Qwen3 model and generate your cloned speech.

---

## ⚖️ License

This project is for educational and research purposes. Please ensure you have the rights to any voice data you use for cloning.

```

---
