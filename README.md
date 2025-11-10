# 🧠 AI Fill The Blanks

A sleek **Cyberpunk-themed React web app** that auto-completes your text using **Google Gemini AI API**.  
Just start typing — the AI continues your sentence naturally, creating an immersive futuristic typing experience.

---

## 🚀 Features

- 🤖 **Gemini-powered text continuation** – AI continues sentences smoothly and contextually  
- ⏳ **Smart debounce** – waits 1.5 seconds after typing stops before calling AI  
- 🌌 **Cyberpunk Hacker UI** – neon glow, matrix scanlines, glitch animations  
- ⚡ **Real-time response rendering** – shows AI completion seamlessly with your text  
- 💬 **Loading indicator** – displays “Thinking…” while AI generates text  

---

## 🧰 Tech Stack

- **React.js** – Frontend framework  
- **Gemini API** – AI text generation  
- **CSS3** – Cyberpunk hacker theme  
- **JavaScript (ES6+)**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/<your-username>/AI-Fill-The-Blanks.git
cd AI-Fill-The-Blanks
npm install

Configure Gemini API
Make sure your Gemini.js looks something like this:

class Gemini {
  async generateContent({ message }) {
    // Replace this with your actual Gemini API call
    // For now, mock a fake AI response
    return new Promise((resolve) => {
      setTimeout(() => {
        resolve(" — and that’s how innovation keeps evolving.");
      }, 1000);
    });
  }
}
export default Gemini;

Run the Development Server
npm start

Demo Screenshot
Add your screenshot here once the app runs:
<img width="1912" height="967" alt="{D537985D-5864-4C92-90BC-919860CA1E46}" src="https://github.com/user-attachments/assets/e6f58878-7e79-42d4-83b6-725985147177" />

