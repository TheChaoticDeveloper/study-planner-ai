Study & Planning AI
This project is licensed under MIT License see LICENSE for details

A personal AI assistant designed to help students create study plans and manage upcoming events.  
Built as a personal project for IB personal project

---

## Features

- Interactive chat interface: chat bubbles and animated typing indicator
- AI-powered responses: using OpenAI GPT API
- Secure backend: deployed on Vercel
- Request limits: preventing overuse and control costs (this was not free)
- Responsive and modern UI: gradients, shadows, and custom scrollbars

---
## Usage

1. Open the index.html in your browser
2. Type a question or request for a study plan
3. Click Send or press Enter
4. The AI responds with a plan or advice
Note: Request limits are enforced to prevent exceeding API usage.

---
## Technology Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js + Vercel Serverless Functions  
- AI: OpenAI GPT API (gpt-4o-mini)  
- Version Control: Git + GitHub  
- Deployment: Vercel

---
## Side note(s): 
Overuse of the AI will result in the developer (me) to pay 5$ as OpenAI only allows you to use their API keys if I have a credit balance of 5$ or more placed my OpenAI account.

API key must remain secret; do not expose in the frontend
Free OpenAI credits can be used initially; further use requires a paid balance
The app is intended for personal use and testing purposes

1,000 or more requests/responses by the AI could result in the developer (me) having to pay 5$ (or more) so it would be appreciated if anyone using my project to send a limited amount of messages to the AI.

Thanks and enjoy my AI

---

## Setup Instructions

### 1. Clone the repository
### 2. Backend Setup:
Create a .env file in backend/: OPENAI_API_KEY=your_openai_api_key_here
Install dependencies: command prompt: cd backend, npm install
Deploy to vercel: command prompt: vercel
### 3. Frontend setup:
The frontend is a static HTML page (index.html)
Ensure the backendUrl in the script points to your deployed Vercel function
---
## Future Improvements

Add session memory to remember user’s study topics

Format study plans as tables or bullet lists

Track daily usage statistics

Add authentication for multiple users

```bash
git clone https://github.com/yourusername/study-planner-ai.git
cd study-planner-ai

