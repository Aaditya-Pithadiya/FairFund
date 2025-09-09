# FairFund
# 🧠 LoanDocGenAI: Generative AI for Automated Loan Analysis

*LoanDocGenAI* is a Generative AI-powered system that automates the evaluation of loan applications by analyzing uploaded PDF documents. The system leverages multi-agent LLM architecture to provide transparent risk scoring, explainability, bias detection, and an interactive chatbot interface — along with insightful visualizations.

---

## 🚀 Project Objective

To automate the loan evaluation process using Generative AI — including:

- 📊 *Risk Scoring*
- 🧠 *Explainability*
- ⚖ *Bias Detection*
- 💬 *Interactive Chatbot*

By analyzing PDF loan documents submitted by users, the system aims to bring fairness, transparency, and efficiency to the loan approval workflow.

---

## 🔑 Key Features

### 📁 Upload Loan Application PDF
Users can upload loan application documents in PDF format through a simple web interface.

### 🤖 Analyze with Generative AI Agents
The system uses specialized GenAI agents to perform:

- *Risk Scoring*  
  Assigns a score (1-100) based on financial and demographic data extracted from the PDF.

- *Explainability*  
  Highlights key features influencing the approval or rejection in clear, human-readable bullet points.

- *Bias Detection*  
  Checks for potential bias in decision-making based on:
  - Gender
  - Location
  - Income level

- *Interactive Q&A Chatbot*  
  Allows users to ask questions about their application analysis in real-time using a context-aware AI assistant.

### 📊 Visual Analytics
The results are presented with intuitive visualizations:

- Risk Score *gauge chart*
- Feature Importance *bar graph*
- Bias Analysis *heatmap*

---

## 🧰 Tech Stack

- *Frontend:* HTML5, Bootstrap 5
- *Backend:* Next
- *Visualization:* Matplotlib, Seaborn
- *AI Models:* IBM watsonx
- *Optional:* MongoDB for storing analysis sessions

---

## 📌 Use Cases

- Automating manual loan underwriting processes
- Improving explainability in credit decisions
- Promoting fair and unbiased lending practices
- Enhancing user trust with interactive explanations

---

## 📂 Coming Soon

- 🔄 Bulk PDF upload
- 🧾 Downloadable report as PDF

# FairFund

FairFund is an AI-powered loan document analysis platform that helps users and providers evaluate loan applications for risk, explainability, and bias. It features a modern web interface, multi-AI assistant architecture, and interactive analytics.

---

## Architecture Overview


[User]
  |
  v
[Next.js Frontend]
  |         |         |         |
  |         |         |         |
[PDF Upload] | [Chatbot] | [Bias Dashboard] | [Analytics]
  |         |         |         |
  v         v         v         v
[API Routes (Node.js)]
  |         |         |         |
  |         |         |         |
[Multi-AI Assistant Logic]
  |         |         |         |
  v         v         v         v
[Results Rendered in UI]


- *Frontend:* Next.js (React, TypeScript), Tailwind CSS
- *Backend:* Next.js API routes (Node.js, TypeScript)
- *AI Assistants:* Multiple dummy AI modules for risk scoring, explainability, and bias detection (can be replaced with real models)
- *PDF Parsing:* Simulated (can use pdf-parse or similar)
- *Vector Search (RAG):* Simulated (can use Pinecone, ChromaDB, FAISS)
- *Visualization:* Recharts for analytics and dashboards

---

## Features

- *PDF Upload:* Users upload loan documents for analysis.
- *Risk Scoring:* Multi-AI assistant estimates risk of loan approval.
- *Explainability:* Multi-AI assistant provides human-readable reasoning for scores.
- *Bias Detection:* Multi-AI assistant checks for potential bias in loan terms.
- *RAG-powered Chatbot:* Answers questions about the uploaded document using retrieval-augmented generation.
- *Analytics Dashboard:* Visualizes risk, bias, and approval trends.
- *Continual Learning:* System can improve with new documents and Q&A pairs.

---

## Tools & Technologies

- *Next.js:* React-based framework for server-side rendering and routing.
- *TypeScript:* Type safety for frontend and backend code.
- *Tailwind CSS:* Utility-first CSS for rapid UI development.
- *Recharts:* Charting library for analytics and dashboards.
- *Lucide-react:* Icon library for UI components.
- *Multi-AI Assistant Architecture:*
  - *Risk Score Assistant:* Calculates risk score using document data.
  - *Explainability Assistant:* Generates explanations for risk scores.
  - *Bias Detection Assistant:* Analyzes document for fairness and bias.
  - *RAG Chatbot Assistant:* Retrieves relevant document sections and answers user/provider questions.
- *API Routes:* /api/analyze-loan and /api/chat for backend logic.

---

## How It Works

1. *User uploads a PDF loan document.*
2. *Frontend sends the document to the backend API.*
3. *Multi-AI assistants analyze the document:*
  - Risk scoring
  - Explainability
  - Bias detection
4. *Results are displayed in the UI.*
5. *User can interact with the RAG-powered chatbot for Q&A.*
6. **Analytics dashboard visualizes trends and metrics.

---

## Extensibility

- Replace dummy AI logic with real models (OpenAI, HuggingFace, custom ML).
- Integrate a database for storing documents, analyses, and feedback.
- Add authentication for user management.
- Deploy on Vercel, Netlify, or any Node.js server.

---

## Getting Started

1. Clone the repository:
  sh
  git clone https://github.com/RitikTiwary519/FairFund.git
  cd FairFund
  
2. Install dependencies:
  sh
  npm install
  
3. Run the development server:
  sh
  npm run dev
  
4. Visit http://localhost:3000 in your browser.

---

## License

MIT
