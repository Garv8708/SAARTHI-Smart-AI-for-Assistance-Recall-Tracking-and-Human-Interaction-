# SAARTHI
🚀 Saarthi + GenAI — AI-Powered Health Assistant
🌟 1. Project Overview
Saarthi + GenAI is an AI-powered health assistant designed to help users understand health-related information through a simple and user-friendly web interface. The project combines a Flask-based web application with a local Large Language Model (LLM) to support health-related conversations and medical document analysis.

🎯 Main Objective: To make health information easier to access and understand using Generative AI.

✨ 2. Key Features
🤖 AI Health Chat: Allows users to ask health-related questions and receive easy-to-understand responses.

📄 Medical PDF Analysis: Supports uploading medical PDF documents and generating summaries or answering questions based on extracted text.

🧠 Local AI Model: Uses Ollama with a compatible language model, such as Llama 3.2, to generate responses locally.

📊 Health Dashboard: Displays health-related information and user profile details.

🎙️ Voice Interaction: Supports browser-based speech recognition where configured.

🔔 Alerts and Reminders: Optional messaging features may be integrated using Twilio, depending on the project configuration.

🛠️ 3. Technologies Used
🐍 Python

🌐 Flask

🎨 HTML, CSS and JavaScript

🦙 Ollama and Llama 3.2

📑 PyPDF

🗄️ SQLite or the configured storage system

📲 Twilio for optional messaging integrations

⚙️ 4. Installation and Setup
📥 Step 1: Download the Repository
Download the project from GitHub and extract it, or clone it using Git.

🐍 Step 2: Create a Virtual Environment
py -m venv .venv

Activate it on Windows:

.venv\Scripts\activate
📦 Step 3: Install Dependencies
If the project contains a requirements.txt file, run:

pip install -r requirements.txt

Otherwise, install the dependencies required by your project files.

🧠 Step 4: Configure Ollama
Install Ollama from https://ollama.com and download the model:

ollama pull llama3.2

Ensure Ollama is running before using the application.

▶️ Step 5: Run the Application
If the main Flask file is named app.py, run:

py app.py

Open the local address displayed in the terminal, commonly:

http://127.0.0.1:5000

📄 5. Medical Document Analysis
Users can upload medical PDF documents through the application interface. The application extracts readable text from the document and uses the AI workflow to generate summaries or respond to questions.

Benefits:

🔍 Easier access to information in medical reports.

📝 AI-generated summaries of readable document content.

💬 Ability to ask questions about uploaded reports.

📌 Support for finding specific medical values when they can be extracted.

⚠️ The accuracy of results depends on the quality and format of the PDF. Scanned documents may require OCR support. Important medical values should always be checked against the original report.

🔐 6. Privacy and Security
🔑 Never upload API keys, passwords or credentials to a public GitHub repository.

🛡️ Keep secret configuration files, such as .env, out of version control.

🧪 Use sample or de-identified medical documents for demonstrations.

🔒 Protect personal and medical information from unauthorized access.

🌐 Configure suitable security measures before deploying the application publicly.

⚠️ 7. Limitations
🤖 AI-generated responses may be incomplete or inaccurate.

📄 PDF text extraction may fail for scanned documents or complex layouts.

🔧 Optional features may require additional configuration and testing.

🧪 Successful code execution does not guarantee that every feature works correctly.

Important: Saarthi is an educational prototype, not a substitute for professional medical advice, diagnosis or treatment.

🔮 8. Future Scope
Potential future improvements include:

🧠 Better medical document retrieval and answer accuracy.

📷 OCR support for scanned medical reports.

🗣️ Improved Hindi voice interaction.

🔐 Secure health data storage and privacy controls.

⏰ More reliable medicine reminders and alerts.

🧪 Comprehensive testing of AI responses and application workflows.

🎯 9. Conclusion
Saarthi + GenAI demonstrates how Generative AI, local language models and web technologies can be combined to build an interactive health information assistant.

💡 The project aims to make health information more understandable and accessible while emphasizing accuracy, privacy and responsible AI use.

❤️ Built with Python, Flask and Generative AI.
