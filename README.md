🧠 AI-Driven Investment Advisor Chatbot

A Generative AI–powered personal finance assistant

📌 Overview

The AI-Driven Investment Advisor Chatbot is an intelligent, conversation-based system designed to assist users with personal finance queries, investment strategy guidance, and market-related knowledge, using secure and responsible AI.
It generates human-like responses, explains concepts clearly, and provides customized insights based on user inputs — without giving direct stock-buy/sell signals, ensuring safety and regulatory compliance.

🚀 Features

Conversational AI for investment & financial guidance

Risk-profile–aware answers (Conservative / Moderate / Aggressive)

Secure handling of API keys (via .env)

PDF export for responses (if enabled)

Real-time advisory flow with user-friendly UI

Citations, data formatting, and long-context conversations

🏗️ Tech Stack

Frontend: React / Next.js

Backend: Node.js

AI Model: Groq (Mixtral / Llama models, depending on configuration)

Styling: CSS / Tailwind (optional)

State Handling: React hooks / Context API

📦 Getting Started
1. Clone the Repo

Using GitHub Web UI, after creating your repo, copy the HTTPS link and run:

git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

2. Install Dependencies
npm install

3. Environment Variables

Create a .env file in the project root:

GROQ_API_KEY=your_key_here
MODEL=llama3-8b-8192  # or the one you selected


Ensure .env is ignored in Git:

# in .gitignore
.env
.env.local


A ./env.template file is provided for reference.

4. Run the Development Server
npm run dev

The app will be available at:

👉 http://localhost:3000

📁 Project Structure
├── public/
├── src/
│   ├── components/
│   ├── pages/ or app/
│   ├── utils/
│   ├── services/
├── .gitignore
├── .env.template
├── package.json
├── README.md

🧪 Running Lint / Formatting
npm run lint
npm run format

🛡 Security Notes

⚠️ NEVER commit the .env file.
⚠️ NEVER expose API keys publicly.
⚠️ The chatbot avoids giving direct investment orders such as:

“Buy this stock”

“Sell this now”

“Guaranteed returns”

The system provides education, analysis, and insight, but not regulated Financial advice.

📤 Deployment (Optional)

The project can be deployed to:

Vercel (recommended for Next.js)

Netlify

Render

Just connect your GitHub repo and set your Environment Variables in the deployment dashboard.

🤝 Contributing

Fork the repository

Create a feature branch

git checkout -b feature/new-module


Commit your changes

Open a Pull Request

📄 License

MIT License (can be changed based on your preference)

📬 Contact

Feel free to open issues or feature requests in the repository.
