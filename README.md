# 📧 AI-Powered Gmail Auto Reply System (n8n + OpenAI)

An intelligent email automation workflow built using **n8n** that reads incoming emails, classifies them, and generates smart, professional replies using **AI (OpenAI GPT-4.1)**.

---

## 🚀 Features

- 📩 Automatic email detection (real-time)
- 📥 Fetch full email content
- 🧠 AI-based email understanding
- 🏷 Smart email classification (labels)
- ✍️ Auto-generated professional replies
- 🧾 Structured output parsing
- ⚡ Fully automated workflow

---

## 🛠 Tech Stack

- **n8n** – Workflow automation  
- **Gmail API** – Email monitoring & fetching  
- **OpenAI (GPT-4.1)** – AI response generation  
- **LangChain Agent** – Prompt handling & logic  
- **Structured Output Parser** – Clean AI output  

---

## 🔄 Workflow Overview

1. Gmail Trigger monitors inbox (every minute)  
2. New email is detected  
3. Full email content is fetched  
4. AI Agent processes:
   - Subject  
   - Email body  
5. AI performs:
   - 🏷 Label classification (abc, himu, xyz)  
   - ✍️ Generates structured HTML reply  
6. Output is parsed into structured format  

---

## 🧩 Nodes Used

- **Gmail Trigger** → Detect incoming emails  
- **Gmail Node (Get Message)** → Fetch email details  
- **AI Agent (LangChain)** → Process email content  
- **OpenAI Chat Model (GPT-4.1)** → Generate reply  
- **Structured Output Parser** → Format response  

---

## 🧠 AI Capabilities

### 🏷 Email Classification
Automatically assigns labels like:
- `abc`
- `himu`
- `xyz`

---

### ✍️ Smart Reply Generation

- Professional tone  
- Detailed explanations (for student queries)  
- Clean HTML formatted email  
- Context-aware responses  

---

## 📧 Example Input

---

## 📤 Example Output

```html
<h3>Understanding JavaScript Loops</h3>
<p>Loops allow you to repeat a block of code multiple times...</p>
``` id="z8v4mn"

---

## ⚙️ Setup Instructions

### 1️⃣ Import Workflow
- Open n8n  
- Import the provided JSON file  

---

### 2️⃣ Configure Credentials

- Connect **Gmail OAuth2**
- Add **OpenAI API Key**

---

### 3️⃣ Activate Workflow

- Turn ON workflow  
- Send a test email  
- Watch AI generate response automatically  

---

## 🔥 Use Cases

- Customer support automation  
- Student query handling  
- Business email automation  
- Personal productivity assistant  
- AI email responder  

---

## 🚧 Future Improvements

- 📤 Auto-send reply directly from workflow  
- 🧠 Advanced intent detection  
- 🏷 Dynamic label creation  
- 📊 Email analytics dashboard  
- 🧑‍💼 CRM integration  

---

## 👨‍💻 Author

**Himujjal Borah**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 📜 License

This project is open-source and free to use.
