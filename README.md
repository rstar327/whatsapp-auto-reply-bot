# 🤖 Auto-Reply-Bot

An automated browser-based bot that reads chat from any browser, uses Groq AI to generate a witty reply, and pastes the response automatically. The bot speaks like Abdul Manan — a sarcastic coder from Pakistan — and roasts people in a funny and natural way.

---

## 🚀 Features

- ✅ Reads chat from any browser (via screen selection)
- 🤖 Uses Groq AI to analyze and reply to last message
- 🔥 Generates humorous, roast-style responses
- 🧠 Only replies if the last message is NOT from Abdul Manan
- 📋 Automatically pastes the response back to input field
- 🖱️ Fully automated using `pyautogui`

---

## 🧠 How It Works

1. Focuses any browser using `wmctrl`
2. Selects a portion of the screen containing chat
3. Copies text using `pyautogui`
4. Extracts the last message and checks the sender
5. If sender ≠ Abdul Manan → calls Groq API for response
6. Pastes the AI-generated message back into chat input

---

## ⚙️ Setup Instructions

### 1. Clone the Repo
git clone https://github.com/rstar327/whatsapp-auto-reply-bot.git
cd whatsapp-auto-reply-bot

### 2. Create a Virtual Environment
python3 -m venv myenv
source myenv/bin/activate

### 3. Install Requirements
pip install -r requirements.txt

🔐 Important Notes
<br/>
This bot uses pyautogui, so screen resolution and mouse positions must be calibrated.
Ensure Brave browser is open and focused on the chat window.
This bot only works on Linux due to use of wmctrl.
GitHub push protection is enabled to block secrets.
<br/>

📦 Dependencies
<div>pyautogui</div>
<div>pyperclip</div>
<div>subprocess</div>
<div>Groq API (via custom groqAi.py)</div>

<br/>
🧪 Example Response
<div>Last Message: [3:12 pm, 20/06/2025] Ammar: Bro, my CNIC got rejected 😂</div>
<div>AI Response: Are you trying to verify your CNIC or applying to NASA? 😂</div>
<br/>
🙋‍♂️ Author
<div>Abdul Manan</div>
<div>Front-end Developer | Python Automation Enthusiast</div>
<div>📍 Karachi, Pakistan</div>
<div>📧 abdul.manan232332@gmail.com</div>
<div>🔗 abdul-manan.vercel.app</div>


