# 🧠 AI Image Generator using Stable Diffusion

## 📌 Project Description
This project is a Generative AI application that converts text into images using the Stable Diffusion model. 
The user provides a text prompt, and the model generates a corresponding image.

---

## 🎯 Objective
To build a simple AI system that can generate realistic images from textual descriptions.

---

## 🛠️ Technologies Used
- Python
- PyTorch
- Diffusers Library
- Transformers
- Google Colab

---

## ⚙️ How It Works
1. Load the pre-trained Stable Diffusion model
2. Take text input from the user
3. Generate image using AI model
4. Display the output image

---

## 💻 Code Example
```python
prompt = "A beautiful girl in anime style"
image = pipe(prompt).images[0]
image
