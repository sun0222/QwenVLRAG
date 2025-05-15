# Qwen2-VL-2B Image/Video Multi-Modal Demo

This is a Gradio-powered web demo for [Qwen2-VL-2B-Instruct](https://huggingface.co/Qwen/Qwen2-VL-2B-Instruct), a vision-language model developed by Qwen. It supports image and video input along with a natural language question to perform multi-modal inference.

## 🔥 Demo Features

- ✅ Accepts both **image** and **video** inputs.
- ✅ Processes user questions and returns intelligent responses based on the visual input.
- ✅ Streaming output using Gradio and Hugging Face `TextIteratorStreamer`.
- ✅ Supports GPU inference via `@spaces.GPU`.

## 🖥️ Live Demo

👉 Try it here: [Live Demo on Hugging Face Spaces](https://huggingface.co/spaces/sunnnil/QwenVLRAG)

---

## 🛠️ Installation

Clone this repository:

```bash
git clone https://github.com/sun0222/QwenVLRAG.git
cd QwenVLRAG

#Create a virtual environment and activate it:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

#Install the dependencies:

pip install -r requirements.txt

#If you don’t have a requirements.txt, use the list below:

pip install numpy==1.24.4
pip install Pillow==10.3.0
pip install requests==2.31.0
pip install torch torchvision
pip install git+https://github.com/huggingface/transformers.git
pip install accelerate
pip install qwen-vl-utils
pip install av
pip install gradio
```
## 🚀 Launch the App
```
python app.py
```
This will start a Gradio interface at http://127.0.0.1:7860.

## 📂 File Structure


- app.py                 # Main application file
- README.md              # Project readme
- requirements.txt       # Package dependencies

## 📸 Supported Formats
Images: PNG, JPG, JPEG, etc.
Videos: MP4, AVI, MOV, MKV, GIF, WEBM, etc.

## 📜 License
This repository uses the Qwen2-VL-2B-Instruct model under its respective license. The rest of the code is open-sourced under the MIT license.

## 🙏 Acknowledgements

- Qwen Team
- Hugging Face Transformers
- Gradio

Developed by Sunil Kumar






