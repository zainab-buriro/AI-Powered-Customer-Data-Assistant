# AI-Powered Customer Data Assistant (n8n + Groq + Google Sheets)

An enterprise automation workflow that replaces manual Google Sheet searching (`Ctrl+F`) with an interactive, natural language AI agent.

### Tech Stack
- **Orchestration:** n8n
- **LLM Reasoning Core:** Groq API (Llama 3.3-70b)
- **Data Source:** Google Sheets API (Customers, Orders, Payments, Support Tickets)
- **Memory:** Simple Memory Node for session continuity

### 📥 How to Use
1. Download the `workflow.json` file from this repository.
2. Open your n8n instance.
3. Go to options (top right `...`) and click **Import from file**.
4. Connect your own Google Sheets and Groq API credentials, and you're ready to go!
