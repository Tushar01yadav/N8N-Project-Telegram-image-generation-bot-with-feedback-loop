# 🖼️ Image Generation Telegram Bot with feedback loop ( Telegram + n8n + Stable Diffusion + Google Drive)

## 📌 Overview
This project is a **Telegram bot powered by n8n** that generates and improves images using the **Stable Diffusion API**.  
The bot provides a smooth interactive flow:
1. Greets the user 👋  
2. Accepts a text prompt 📝  
3. Generates an image 🎨  (text-to-image generation )
4. Uploads the generated image to **Google Drive** ☁️
5. Asks for improvement 🔄  
6. Takes the improvement prompt and regenerates the image with **consistency** ( means improve the same image not creating a new one )/ image-to-image generation with additional prompt
7. Replaces the old image in Google Drive with the **refined version**  
Screenshot: 
<img width="649" height="280" alt="7" src="https://github.com/user-attachments/assets/11adaf86-abcd-4297-bd45-257a38219cb9" />


This makes it easy to create, refine, and store AI-generated images directly from Telegram.

---

## ⚡ Features
- 🤖 Telegram Bot integration via n8n  
- 🖼️ Image generation using **Stable Diffusion API**  
- 🔄 Image refinement with improvement prompts  
- 💬 Interactive conversation flow (greet → generate → feedback → improve)  
- 🎯 Consistent results across refinements  
- ☁️ **Google Drive upload support** – auto-uploads generated images, replaces old versions with improved ones  

---

## 🛠️ Tech Stack
- **n8n** – workflow automation  
- **Telegram Bot API** – user interaction  
- **Stable Diffusion API** – image generation and enhancement  
- **Google Drive API** – cloud storage & replacement  
- **JavaScript/JSON (n8n workflows)**  

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/image-gen-telegram-bot.git
cd image-gen-telegram-bot
-telegram-bot.git
cd image-gen-telegram-bot
