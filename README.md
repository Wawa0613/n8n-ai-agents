# 🤖 n8n AI Agents Collection

This repository contains a set of intelligent automation workflows built with **n8n**.  
Each agent combines **Google Gemini APIs**, **LangChain-style prompt logic**, and **HTTP automation nodes** to perform creative and data-driven tasks automatically.

These agents are designed for **creators, designers, and digital entrepreneurs** who want to explore how AI can automate idea generation, trend analysis, and creative workflows — all inside n8n.

---

## 🧠 Included Agents

| Agent | Purpose | Description |
|--------|----------|-------------|
| **Moodboard Agent** | Visual Inspiration Generator | Converts short creative prompts (e.g., “modern neutral living room with wooden textures”) into detailed text prompts and automatically generates moodboard-style visuals using **Gemini Image Generation API**. It cleans the input, expands the concept, and produces images ready for design inspiration. |
| **Market Trend Discovery Agent** | AI Trend Analyst | Detects whether a user query is related to home decor or rug trends, then fetches and analyzes the latest RSS feeds from **The Ruggist**, **House Beautiful**, **Design Milk**, and **Dezeen**. The agent summarizes insights into concise, actionable updates. |

---

## 💡 Use Cases

- 🎨 **For Designers:** Quickly generate visual inspiration for projects.  
- 📰 **For Marketers:** Discover emerging home & decor trends automatically.  
- ⚙️ **For Developers:** Learn how to connect Gemini APIs with n8n via HTTP requests and prompt logic.

---

## ⚙️ Tech Stack & Architecture

- **n8n (self-hosted Docker / Cloud)** — visual automation builder  
- **Google Gemini API** — text + image generation & analysis  
- **LangChain / Prompt Engineering** — structured AI reasoning inside code nodes  
- **HTTP Request Nodes** — connect external APIs and RSS data sources  
- **JavaScript Code Nodes** — data parsing, prompt cleanup, and control flow  
- **Environment Variables (.env)** — securely store API keys (not included in exports)

---

## 🪄 How to Use

### Import an Agent
1. Download any `.json` file from the [`agents/`](./agents) folder.  
2. Open your n8n dashboard.  
3. Go to **Workflows → Import from File** → select the `.json` file.  
4. Add your own credentials (e.g., Gemini API Key) and activate the workflow.

### Export a Workflow
1. Open your workflow in n8n.  
2. Click **⋯ (three dots)** → **Download**.  
3. Before sharing, remove any credentials or replace them with environment variables.  
4. Upload the cleaned `.json` file to this repository.

---
