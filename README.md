<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&pause=1000&color=F7F7F7&center=true&vCenter=true&width=900&lines=+Nexus+AI+Booking+Agent" alt="Title" />
</div>

An autonomous, AI-driven appointment booking workflow built on n8n. It leverages advanced LLM capabilities to chat with users, extract scheduling details dynamically, and manage calendar events automatically.

---

### 📦 Stack
- n8n (Workflow Automation)
- LangChain (Agent & Memory Orchestration)
- Gemini 2.5 Flash (Google AI)
- Google Calendar API

---

### ✨ Quick start
```bash
# Clone the repository
git clone https://github.com/wayne2604/nexus-ai.git

# Navigate to the directory
cd nexus-ai
```
Import the `nexus-ai.json` workflow file into your n8n instance and configure your credentials to get started.

---

### ⚙️ Features
- **Secure Auth / Chat Integration**  Engage with users naturally using specialized nodes to capture booking intent and details.
- **Schedule Management**  Create, view, and delete daily calendar slots or appointments automatically.
- **Search Logic**  Efficient query logic to check existing calendar schedules before booking.
- **Orchestration & Memory**  Utilizes memory-buffered agent logic to remember chat details across conversations.

---

### 🛠️ How it works
The system follows a modular architecture designed for high reliability and ease of use:
- **Database / API Connectivity**: Integrates directly with the Google Calendar API using secure OAuth credentials to query slot availability and book events.
- **Decoupled Logic**: Separate routing of user chats, backend parsing via LLMs, and webhook executions for better scalability.
- **AI Agent System**: Employs LangChain configurations powered by Gemini 2.5 Flash to dynamically interpret unstructured scheduling messages.

---

### 📁 Project structure
```text
/
 workflows/              # Core workflow files for n8n
  nexus-ai.json          # Main booking agent workflow JSON export
 assets/                 # Documentation assets and schemas
 README.md               # Project documentation
```

---

### 👤 Author
**Wayne**  [github.com/wayne2604](https://github.com/wayne2604)
