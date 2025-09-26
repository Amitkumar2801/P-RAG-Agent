# 🚀 P-RAG-Agent-by-CHAMGADAR: Personalized RAG-Based Learning System

### Project Overview
This project develops a **Personalized Retrieval-Augmented Generation (P-RAG) Agent**, a sophisticated AI tutor that teaches complex topics using a custom knowledge base (PDFs, documents). Unlike general chatbots, this system leverages a **Multi-Agent Architecture** to deliver a structured, personalized, and verifiable learning experience.

### Key Features (Core Agents)
Our system consists of a team of specialized AI Agents that collaborate to educate the user:

1.  **🧠 Prior Knowledge Assessor (Agent A):**
    * Tests the user's initial understanding to create a custom learning path.
2.  **📚 Curriculum & Content Agent (Agent B):**
    * Breaks down the topic into modules and uses **RAG** to fetch and simplify content *directly* from the uploaded knowledge base (PDFs).
3.  **📝 Quiz & Feedback Agent (Agent C):**
    * Generates module-specific quizzes based on the RAG content to check understanding and scores the answers.
4.  **📣 Motivation & Coach Agent (Agent D):**
    * Provides empathetic, performance-based feedback and encouragement to optimize the learning curve.

### Core Technology Stack
| Component | Technology Used | Purpose |
| :--- | :--- | :--- |
| **LLMs/AI** | OpenAI GPT-4 / Gemini (ya Llama) | Core intelligence and reasoning for all agents. |
| **RAG** | LangChain, ChromaDB, pypdf | Creating and querying the custom knowledge base. |
| **Backend** | Python, Flask/FastAPI (Future) | Orchestrating agent workflow and serving the application. |

### 🛠️ Getting Started (Setup)

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Rmitkumar2801/P-RAG-Agent-by-CHAMGADAR.git](https://github.com/Rmitkumar2801/P-RAG-Agent-by-CHAMGADAR.git)
    cd P-RAG-Agent-by-CHAMGADAR
    ```
2.  **Environment Setup:** Create and activate a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate  # or .\venv\Scripts\activate on Windows
    ```
3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt 
    # Note: We will create the requirements.txt file in the next step.
    ```
4.  **API Key:** Create a `.env` file and add your key:
    ```
    OPENAI_API_KEY="your_api_key_here"
    ```

### Status: In Progress 🚧

---

