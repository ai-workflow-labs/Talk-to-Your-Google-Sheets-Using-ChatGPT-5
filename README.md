<img width="485" height="479" alt="image" src="https://github.com/user-attachments/assets/73dc2477-5f09-4bb9-9857-458988b9df3c" />

# 🤖 AI-Powered Data Q&A Workflow

Welcome to the **Smart Data Analysis Workflow**!  
This workflow lets you **chat directly with your Google Sheets data**, ask natural language questions, and get instant insights powered by AI. 💡  

---

## 🌟 What This Workflow Does

### 💬 Chat Interface
Provides a conversational interface where you can ask questions about your data in plain English.

### 🧠 Smart Data Analysis
Automatically understands column structures and relationships in your dataset to deliver meaningful insights.

### 📊 Google Sheets Integration
Connects directly to your **Google Sheets**, so you can analyze live data without manual exports.

### 🧩 Memory Buffer
Keeps track of your conversation context — perfect for follow-up questions and deeper analysis.

### 🔍 Automated Column Detection
Detects and describes your data columns automatically, so you can start analyzing right away.

---

## 🚀 Getting Started

### 1️⃣ Set Up Your OpenAI Connection

#### 🗝️ Get Your API Key
1. Go to the [OpenAI API Keys page](https://platform.openai.com/account/api-keys)  
2. Visit [OpenAI Billing](https://platform.openai.com/account/billing/overview) and **add funds**  
3. Copy your API key into your OpenAI credentials in **n8n** (or your preferred automation platform)

---

### 2️⃣ Prepare Your Google Sheet

#### 📋 Connect Your Data
Make sure your Google Sheet follows this format:

| Campaign | Channel | Spend | Conversions | Date |
|-----------|----------|--------|--------------|------|
| Example Campaign 1 | Paid Search | 1200 | 45 | 2025-01-01 |

✅ **Requirements:**
- The **first row** contains **column names**
- Data is in **rows 2–100**
- Connect via **OAuth** and select your **workbook** and **sheet**

---

### 3️⃣ Ask Questions About Your Data 🧮

You can now ask natural language questions such as:

> 💬 "What is the total spend across all campaigns?"  
> 💬 "Show me the spend for Paid Search only."  
> 💬 "How has ad spend changed month over month?"  
> 💬 "Which campaigns have the highest conversion rate?"  
> 💬 "What’s the cost per lead for each marketing channel?"

---

## ⚙️ Example Use Cases

- 📈 **Marketing Performance Analysis**
- 💸 **Budget Tracking**
- 🎯 **Campaign Optimization**
- 🧾 **Automated Reporting**

---

## 💡 Pro Tip
Keep your data clean and consistent — the AI performs best when your columns have clear names like:
`Campaign`, `Spend`, `Clicks`, `Leads`, `Date`, `Channel`.


