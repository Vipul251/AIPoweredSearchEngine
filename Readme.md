⚡ Advanced Search Engine with LangChain Mistral + Groq
🚀 Overview
This project is an AI-powered advanced search engine built using LangChain and Mistral models, optimized with Groq’s ultra-fast TSP (Tensor Streaming Processor) infrastructure. It offers blazing-fast inference, real-time search capabilities, and conversational memory, making it ideal for dynamic applications like:

Customer support

Technical troubleshooting

Sales assistance

Knowledge base search

By integrating Groq API with LangChain, the system minimizes latency while maintaining high model performance and response quality.

⚙️ Optimization with Groq
Groq’s hardware acceleration enables:

Real-time inference

Low-latency LLM responses

Scalability for high-volume user queries

We leverage Mixtral 8x7B and LangChain's framework for memory-aware, high-speed conversational AI deployment using Streamlit as the front-end interface.

🧠 Key Features
🔍 AI-Powered Search: Understands natural queries via LangChain Mistral models.

🧠 Conversational Memory: Remembers chat history to give smarter, contextual responses.

🧩 Custom LLM Selection: Choose among multiple LangChain-supported Mistral models.

⚡ Groq TSP Optimization: Delivers ultra-low latency with Groq's inference engine.

🧑‍💻 Streamlit UI: Simple and elegant front-end for interaction and testing.

🛠️ Installation & Usage
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your_username/advanced-langchain-groq-chatbot.git
cd advanced-langchain-groq-chatbot
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Set Configuration (Optional)
You can modify the configuration variables in a .env or Python config file:

env
Copy
Edit
GROQ_API_KEY=your_groq_api_key_here
DEFAULT_MODEL=mistral-8x7b
CONVERSATIONAL_MEMORY_LENGTH=3
4. Run the Application
bash
Copy
Edit
streamlit run app.py
5. Open in Browser
Local URL: http://localhost:8501

Network URL: http://192.168.164.151:8501

🧾 Configuration Reference
Config Variable	Description
groq_api_key	Your Groq API key for accessing the model
default_model	LangChain-compatible Mistral model name
conversational_memory_length	Number of previous interactions to remember

🐍 Code Optimization Note
⚠️ Deprecation Warning
LangChain's __call__() method is deprecated. You should use the updated invoke() method instead to ensure future compatibility.

python
Copy
Edit
# Replace this (deprecated):
response = llm(prompt)

# With this (recommended):
response = llm.invoke(prompt)
🎯 Use Cases
Real-time enterprise chatbot for technical support

AI-powered helpdesk interface

Knowledge base document retriever

Sales assistant powered by LLMs

📬 Contact
Have questions or ideas to contribute?

📧 Email: contact.vipulbhatt@gmail.com

📄 License
This project is open-source and available under the MIT License.
