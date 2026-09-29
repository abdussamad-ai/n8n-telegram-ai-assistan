# n8n-telegram-ai-assistan
# 🚀 Multimodal Telegram AI Assistant (n8n + Google Gemini)

An automated, context-aware Telegram AI Agent built with **n8n** and powered by **Google Gemini**. This workflow seamlessly processes both **Text** and **Voice** interactions, providing intelligent responses while preserving the original input modality and language context.

---

## ✨ Key Features

- **🔀 Smart Input Routing:** Automatically distinguishes between incoming text messages and voice notes using n8n Switch nodes[cite: 3].
- **🎙️ Voice-to-Text Transcription:** Transcribes audio recordings via Google Gemini (`gemini-3-flash-preview`)[cite: 3].
- **🧠 Context-Aware AI Agent:** Powered by Gemini Chat Model to deliver natural, accurate, and concise replies[cite: 3].
- **🌐 Multilingual Support:** Responds fluently in the user's language, including full Bengali (বাংলা) and English code-switching support[cite: 3].
- **⚡ Low-Code Orchestration:** Easily deployable and configurable on any self-hosted n8n instance[cite: 3].

---

## 🛠️ Workflow Architecture

1. **Telegram Trigger:** Listens for incoming user updates[cite: 3].
2. **Switch Node 1:** Routes message based on input type (`text` vs. `voice`)[cite: 3].
3. **Transcription Pipeline:** Converts voice notes to text using Gemini Audio processing[cite: 3].
4. **AI Agent Processing:** Evaluates input, applies system instructions, and generates responses[cite: 3].
5. **Switch Node 2:** Directs output to send text replies or audio messages based on initial request type[cite: 3].

---

## 🚀 How to Use / Import

1. **Clone or Download** this repository.
2. Open your **n8n Canvas**.
3. Click on the top-right menu **`⋮`** → **`Import from File`**.
4. Select the `My workflow 3 (1).json` file from this repository[cite: 3].
5. Configure your API Credentials in n8n:
   - **Telegram API Credentials**[cite: 3]
   - **Google Gemini (PaLM) API Credentials**[cite: 3]
6. Activate the workflow! 🎉

---

## 📋 Tech Stack

- **Automation:** [n8n](https://n8n.io/) (Self-Hosted)[cite: 3]
- **AI / LLM:** Google Gemini API (`gemini-3-flash-preview` & Chat Model)[cite: 3]
- **Platform:** Telegram Bot API[cite: 3]

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
