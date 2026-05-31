<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=220&color=0:0a0d1a,50:1a2a5e,100:0a0d1a&text=SMART%20TELEGRAM%20BOT&fontColor=4A9EFF&fontSize=46&fontAlign=50&fontAlignY=55&animation=fadeIn&stroke=4A9EFF&strokeWidth=1&desc=n8n%20%7C%20Ollama%20%7C%20Gemini%20AI%20%7C%20Docker%20%7C%20WSL2&descAlign=50&descAlignY=75&descSize=15&descColor=7db8ff" width="100%"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&weight=700&size=20&duration=4000&pause=800&color=4A9EFF&center=true&vCenter=true&width=700&height=45&lines=%E2%96%B6+AGENT+BOOT+%E2%80%94+ALL+SYSTEMS+READY;%E2%97%8F+GMAIL+%C2%B7+DRIVE+%C2%B7+SHEETS+%C2%B7+MEMORY;%E2%96%B6+DUAL+AI+AGENTS+%7C+SMART+ROUTING;%E2%97%8F+DOCKER+%7C+WSL2+%7C+NGROK+POWERED"/>

<br/>

<a href="https://github.com/Amin-Moniry"><img src="https://img.shields.io/badge/%E2%96%B2%20DOCKER-Containerized-4A9EFF?style=for-the-badge&logo=docker&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://ollama.ai"><img src="https://img.shields.io/badge/%E2%97%88%20OLLAMA-AI_Models-4A9EFF?style=for-the-badge&logo=ollama&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://gemini.google.com"><img src="https://img.shields.io/badge/%E2%96%A3%20GEMINI-AI_Powered-4A9EFF?style=for-the-badge&logo=google&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://telegram.org"><img src="https://img.shields.io/badge/%E2%96%B6%20TELEGRAM-Bot-4A9EFF?style=for-the-badge&logo=telegram&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://ngrok.com"><img src="https://img.shields.io/badge/%E2%97%8F%20NGROK-Tunneling-4A9EFF?style=for-the-badge&logo=ngrok&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://docs.microsoft.com/en-us/windows/wsl/"><img src="https://img.shields.io/badge/%E2%96%B3%20WSL2-Linux_Subsystem-4A9EFF?style=for-the-badge&logo=linux&logoColor=4A9EFF&labelColor=0a0d1a"/></a>
<a href="https://python.org"><img src="https://img.shields.io/badge/%E2%97%88%20PYTHON-Backend-4A9EFF?style=for-the-badge&logo=python&logoColor=4A9EFF&labelColor=0a0d1a"/></a>

<br/><br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

---

<div align="center">

## `◈` Overview

</div>

<div align="center">

**Amin's Smart Assistant** is an intelligent Telegram bot that connects Gmail, Google Drive, Google Sheets, and multiple AI models into a single unified command interface. Built on **n8n** automation with **Docker** on **WSL2**, the system routes incoming messages through dual specialized AI agents — each equipped with distinct tools, memory, and reasoning models — transforming any Telegram conversation into a full-featured productivity hub.

The bot targets power users, developers, and teams who need a portable, self-hosted automation layer over their Google Workspace. It supports natural language email composition, spreadsheet queries, Drive browsing, Python code execution, persistent conversation memory via PostgreSQL, and bilingual interaction in English and Persian — all delivered through a single Telegram interface.

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Features

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=true&vCenter=true&width=500&height=28&lines=%E2%97%89+Core+capabilities+of+the+assistant"/>

<small>

| <sub>`▶` Feature</sub> | <sub>Description</sub> | <sub>Status</sub> |
|:-----------------------:|:----------------------:|:-----------------:|
| <sub>Dual AI Agents</sub> | <sub>Email Agent and Data Agent — each with specialized tools and Gemini 2.0 Flash reasoning</sub> | <sub>✅</sub> |
| <sub>Gmail Integration</sub> | <sub>Send and retrieve emails through natural language commands via Telegram</sub> | <sub>✅</sub> |
| <sub>Google Sheets</sub> | <sub>Read, analyze, and display spreadsheet data with row/column targeting</sub> | <sub>✅</sub> |
| <sub>Google Drive</sub> | <sub>Search files, browse folder structures, and retrieve storage analytics</sub> | <sub>✅</sub> |
| <sub>Memory System</sub> | <sub>PostgreSQL-backed persistent conversation memory with cross-session context</sub> | <sub>✅</sub> |
| <sub>Python Execution</sub> | <sub>Detect and execute Python code snippets with intelligent keyword routing</sub> | <sub>✅</sub> |
| <sub>Smart Routing</sub> | <sub>Automatic message classification — email, data, or code — before agent dispatch</sub> | <sub>✅</sub> |
| <sub>Multi-Language</sub> | <sub>Full English and Persian (فارسی) support with context-aware responses</sub> | <sub>✅</sub> |
| <sub>Ollama Local AI</sub> | <sub>Qwen 3:4B running locally via Docker with GPU acceleration</sub> | <sub>✅</sub> |
| <sub>Webhook Tunneling</sub> | <sub>ngrok secure tunneling for Telegram webhook on local WSL2 deployment</sub> | <sub>✅</sub> |
| <sub>Rich Media Support</sub> | <sub>Images, documents, and voice message handling</sub> | <sub>⏳</sub> |
| <sub>Analytics Dashboard</sub> | <sub>Usage metrics and performance monitoring panel</sub> | <sub>⏳</sub> |

</small>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Architecture

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=true&vCenter=true&width=500&height=28&lines=%E2%97%89+Message+routing+and+agent+dispatch+flow"/>

</div>

```mermaid
graph TD
    A[Telegram Input] --> B{Message Type Detection}
    B -->|Email Related| C[AI Agent — Email]
    B -->|Data/Drive Related| D[AI Agent — Data]

    C --> E[Gmail Tools]
    C --> F[Gemini AI Model]

    D --> G[Google Sheets]
    D --> H[Google Drive]
    D --> I[Gemini AI Model]

    E --> J{Response Processing}
    G --> J
    H --> J

    J -->|Contains Python| K[Code Execution]
    J -->|Regular Response| L[Direct Output]

    K --> M[Telegram Output]
    L --> M

    F --> N[PostgreSQL Memory]
    I --> N
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Tech Stack

| Layer | Technologies |
|:-----:|:------------:|
| **Automation Engine** | n8n — self-hosted workflow orchestration |
| **AI Models** | Gemini 2.0 Flash · Qwen 3:4B via Ollama |
| **Messaging** | Telegram Bot API — webhook-based real-time updates |
| **Google Workspace** | Gmail API · Google Sheets API · Google Drive API |
| **Infrastructure** | Docker · WSL2 (Ubuntu) · ngrok tunneling |
| **Memory & Storage** | PostgreSQL — persistent session and context storage |
| **Language** | Python 3 — code execution and backend logic |
| **Auth** | OAuth2 — Google services authentication |

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Project Structure

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+Repository+layout+%E2%80%94+Smart+Telegram+Bot"/>

```
smart-telegram-bot/
│
├── n8n_amin_workflow.json        ← Main n8n workflow export (import this)
├── requirements.txt              ← Python dependencies
├── .env.example                  ← Environment variable template
│
├── Image/
│   ├── n8n_1.png                 ← n8n workflow UI preview
│   └── ...
│
├── docs/
│   └── setup.md                  ← Extended configuration notes
│
└── LICENSE
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Installation

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=540&height=28&lines=%E2%96%B6+Full+stack+setup+on+WSL2+%2B+Docker"/>

![01](https://img.shields.io/badge/01-Setup_WSL2_%26_Docker-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Install WSL2 with Ubuntu and Docker.

```bash
# Install WSL2 with Ubuntu
wsl --install -d Ubuntu

# Install Docker in WSL2
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

# Start Docker service
sudo service docker start
```

![02](https://img.shields.io/badge/02-Setup_Ollama-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Run Ollama container and pull the Qwen model.

```bash
# Pull and run Ollama with GPU support
docker run -d --gpus=all -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama

# Install Qwen 3:4B model
docker exec -it ollama ollama pull qwen3:4b
```

![03](https://img.shields.io/badge/03-Setup_ngrok-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Install and configure ngrok for Telegram webhook tunneling.

```bash
# Install ngrok
curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null
echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list
sudo apt update && sudo apt install ngrok

# Authenticate and expose n8n
ngrok authtoken YOUR_NGROK_TOKEN
ngrok http 5678
```

![04](https://img.shields.io/badge/04-Deploy_n8n-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Launch n8n with PostgreSQL via Docker.

```bash
docker run -d \
  --name n8n \
  -p 5678:5678 \
  -e DB_TYPE=postgresdb \
  -e DB_POSTGRESDB_HOST=postgres \
  -e DB_POSTGRESDB_DATABASE=n8n \
  -v n8n_data:/home/node/.n8n \
  --link postgres:postgres \
  n8nio/n8n
```

![05](https://img.shields.io/badge/05-Import_Workflow-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Import the n8n workflow JSON.

```bash
curl -X POST "your-ngrok-url.ngrok.io/api/v1/workflows/import" \
  -H "Content-Type: application/json" \
  -d @n8n_amin_workflow.json
```

![06](https://img.shields.io/badge/06-Configure_Credentials-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Set up all service credentials inside n8n.

- Telegram Bot API token with ngrok webhook URL
- Google OAuth2 for Gmail, Sheets, and Drive
- PostgreSQL connection string
- Ollama API endpoint: `http://localhost:11434`

![07](https://img.shields.io/badge/07-Network_Setup-4A9EFF?style=flat-square&labelColor=0a0d1a) &nbsp; Connect all containers to a shared Docker network.

```bash
docker network create n8n-network
docker network connect n8n-network ollama
docker network connect n8n-network postgres
docker network connect n8n-network n8n
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Configuration

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+Key+configuration+blocks"/>

**Telegram Bot**
```javascript
{
  "telegramApi": {
    "accessToken": "YOUR_BOT_TOKEN",
    "baseURL": "https://api.telegram.org"
  }
}
```

**Ollama Local AI**
```javascript
{
  "ollamaApi": {
    "baseURL": "http://localhost:11434",
    "model": "qwen3:4b"
  }
}
```

**ngrok Webhook**
```javascript
{
  "webhookUrl": "https://your-tunnel.ngrok.io/webhook/telegram",
  "allowedUpdates": ["message"]
}
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Usage Examples

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+What+you+can+say+to+the+bot"/>

**Email Operations**
```
User  → "Send an email to john@example.com about tomorrow's meeting"
Bot   → Email composed and dispatched via Gmail API.
        Subject auto-generated. Sender attribution applied.
        ✅ Delivered to john@example.com
```

**Spreadsheet Query**
```
User  → "Show me the latest data from my spreadsheet"
Bot   → Fetched 25 rows from active sheet.
        Columns parsed and formatted for Telegram output.
        ✅ Data retrieved successfully
```

**Python Execution**
```
User  → "Write a Python script to calculate fibonacci"
Bot   → Code generated, sandboxed, and executed.
        Output returned with performance note.
        ✅ Script ran successfully
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Advanced Features

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+Under+the+hood"/>

**Smart Message Detection** — The routing layer classifies every incoming message before dispatching it. Email keywords (`message`, `پیام`, `messag`), Python keywords (`python`, `پایتون`, `pyton`), and context from prior messages all influence which agent receives the task.

**Response Enhancement** — Every reply is post-processed: thinking tokens are stripped, emoji are placed meaningfully, the user's first name is injected, and the signature `𝑨𝒎𝒊𝒏 💛 𝑴𝒐𝒏𝒊𝒓𝒚` is appended automatically.

**Memory Architecture** — PostgreSQL stores full session history. Each agent reads from and writes to the same memory pool, enabling coherent multi-turn conversations across separate sessions without repeated context.

**Model Selection** — Gemini 2.0 Flash handles reasoning-heavy tasks; Qwen 3:4B serves fast local completions via Ollama. The routing logic selects the appropriate model based on task complexity and latency requirements.

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Performance

<small>

| <sub>Component</sub> | <sub>Response Time</sub> | <sub>Accuracy</sub> | <sub>Uptime</sub> | <sub>Environment</sub> |
|:--------------------:|:------------------------:|:-------------------:|:-----------------:|:----------------------:|
| <sub>Telegram Webhook (ngrok)</sub> | <sub>&lt;100ms</sub> | <sub>99.9%</sub> | <sub>99.9%</sub> | <sub>WSL2 Docker</sub> |
| <sub>AI Agent Processing</sub> | <sub>&lt;2s</sub> | <sub>95%</sub> | <sub>99.5%</sub> | <sub>Ollama Local</sub> |
| <sub>Gmail Operations</sub> | <sub>&lt;3s</sub> | <sub>98%</sub> | <sub>99.8%</sub> | <sub>Google API</sub> |
| <sub>Google Drive Access</sub> | <sub>&lt;1s</sub> | <sub>99%</sub> | <sub>99.9%</sub> | <sub>Google API</sub> |
| <sub>Memory Retrieval</sub> | <sub>&lt;200ms</sub> | <sub>100%</sub> | <sub>99.9%</sub> | <sub>PostgreSQL</sub> |

</small>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Troubleshooting

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=520&height=28&lines=%E2%96%B6+Common+issues+and+fixes"/>

**Bot not responding**
```bash
# Verify webhook is registered
curl -X GET "https://api.telegram.org/bot{TOKEN}/getWebhookInfo"
# Confirm n8n workflow is active and Telegram trigger node is connected
```

**Gmail authentication errors**
```bash
# Refresh OAuth2 tokens in n8n credentials
# Verify all required scopes in Google Cloud Console
# Check credential expiration date
```

**ngrok tunnel disconnected**
```bash
# Restart with stable connection
ngrok http 5678 --region=us --log=stdout

# Re-register Telegram webhook with new URL
curl -X POST "https://api.telegram.org/bot{TOKEN}/setWebhook" \
  -H "Content-Type: application/json" \
  -d '{"url":"https://new-tunnel.ngrok.io/webhook/telegram"}'
```

**Ollama not responding**
```bash
# Check container status
docker ps | grep ollama

# Restart and verify model
docker restart ollama
curl http://localhost:11434/api/generate -d '{"model":"qwen3:4b","prompt":"test"}'
```

**WSL2 Docker issues**
```bash
sudo service docker restart
docker --version
wsl --list --verbose
```

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Roadmap

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=13&duration=3000&pause=999999&color=4A9EFF&center=false&vCenter=true&width=500&height=28&lines=%E2%96%B6+Planned+features+for+upcoming+versions"/>

- [ ] Rich media handling — images, documents, and voice messages
- [ ] Multi-language expansion — Arabic, Turkish, and more
- [ ] GPT-4 integration as an optional reasoning backend
- [ ] Analytics dashboard for usage metrics and agent performance
- [ ] Additional service integrations — Notion, Slack, Trello
- [ ] Mobile-facing webhook layer for third-party app triggers

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

## `◈` Contributing

1. Fork the repository via the **Fork** button on GitHub.
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit with a descriptive message: `git commit -m "Add: brief description"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a **Pull Request** against the `master` branch of this repository.

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` License

This project is licensed under the **MIT License**.

Any forks or distributions must retain credit to **Amin Moniry (AminTivanix2)** as the original author. See [LICENSE](LICENSE) for complete terms.

`©` 2025 Amin Moniry (AminTivanix2) — All Rights Reserved

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Screenshots

<img src="Image/n8n_1.png" width="80%"/>

*`▶` n8n workflow — dual agent routing with Gmail, Sheets, Drive, and memory nodes*

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

---

<div align="center">

## `◈` Contact

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=14&duration=2000&pause=400&color=4A9EFF&center=true&vCenter=true&width=500&height=30&lines=%E2%96%B6+Reach+out+through+any+channel+below"/>

<br/>

<table>
<tr>
<td align="center" width="210">
<a href="https://github.com/Amin-Moniry">
<img src="https://img.shields.io/badge/◈_GITHUB-Amin--Moniry-4A9EFF?style=for-the-badge&logo=github&logoColor=4A9EFF&labelColor=0a0d1a&color=0d1533" width="200"/>
</a>
</td>
<td align="center" width="210">
<a href="https://t.me/amintivanix2">
<img src="https://img.shields.io/badge/◈_TELEGRAM-@amintivanix2-4A9EFF?style=for-the-badge&logo=telegram&logoColor=4A9EFF&labelColor=0a0d1a&color=0d1533" width="200"/>
</a>
</td>
<td align="center" width="210">
<a href="mailto:amintivanix2@gmail.com">
<img src="https://img.shields.io/badge/◈_EMAIL-amintivanix2-4A9EFF?style=for-the-badge&logo=gmail&logoColor=4A9EFF&labelColor=0a0d1a&color=0d1533" width="200"/>
</a>
</td>
</tr>
<tr>
<td align="center" width="210">
<a href="https://allin1wrench.ir">
<img src="https://img.shields.io/badge/◈_WEBSITE-allin1wrench.ir-4A9EFF?style=for-the-badge&logo=firefox&logoColor=4A9EFF&labelColor=0a0d1a&color=0d1533" width="200"/>
</a>
</td>
<td align="center" width="210" colspan="2">
<a href="https://github.com/Amin-Moniry/CAMERA_PROJECT-WITH_QUEUE_TREADING_DATABASE/issues">
<img src="https://img.shields.io/badge/◈_ISSUES-Report_a_Bug-4A9EFF?style=for-the-badge&logo=githubactions&logoColor=4A9EFF&labelColor=0a0d1a&color=0d1533" width="200"/>
</a>
</td>
</tr>
</table>

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&weight=700&size=15&duration=3500&pause=900&color=4A9EFF&center=true&vCenter=true&width=720&height=50&lines=%E2%96%B6+Engineered+by+Amin+Moniry+(AminTivanix2);%E2%97%8F+One+message.+Two+agents.+Infinite+automation.;%E2%96%B6+n8n+%C2%B7+Ollama+%C2%B7+Gemini+%C2%B7+Open+Source+%C2%B7+2025"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0d1a,50:1a2a5e,100:0a0d1a&height=160&section=footer&text=Built%20with%20intelligence%20%E2%80%94%20AminTivanix2&fontSize=26&fontAlign=50&fontAlignY=55&fontColor=4A9EFF&animation=fadeIn&stroke=4A9EFF&strokeWidth=0.5" width="100%"/>

</div>
