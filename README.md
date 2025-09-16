# 🖼️ Image Generation Telegram Bot with feedback loop (n8n + Stable Diffusion)

## 📌 Overview
This project is a **Telegram bot powered by n8n** that generates and improves images using the **Stable Diffusion API**.  
The bot provides a smooth interactive flow:
1. Greets the user 👋  
2. Accepts a text prompt 📝  
3. Generates an image 🎨  (text-to-image generation )
4. Asks for improvement 🔄  
5. Takes the improvement prompt and regenerates the image with **consistency** ( means improve the same image not creating a new one )/ image-to-image generation with additional prompt  

This makes it easy to create and refine AI-generated images directly from Telegram.

---

## ⚡ Features
- 🤖 Telegram Bot integration via n8n  
- 🖼️ Image generation using **Stable Diffusion API**  
- 🔄 Image refinement with improvement prompts  
- 💬 Interactive conversation flow (greet → generate → feedback → improve)  
- 🎯 Consistent results across refinements  

---

## 🛠️ Tech Stack
- **n8n** – workflow automation  
- **Telegram Bot API** – user interaction  
- **Stable Diffusion API** – image generation and enhancement  
- **JavaScript/JSON (n8n workflows)**  

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/image-gen-telegram-bot.git
cd image-gen-telegram-bot
