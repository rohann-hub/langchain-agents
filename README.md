# Langchain Agents Project 🚀

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)

Welcome to the **Langchain Agents Project**! This repository explores the capabilities of large language models (LLMs) and agentic workflows using the LangChain ecosystem. It integrates multiple state-of-the-art providers, including OpenAI, Google GenAI, and Groq, to build powerful AI-driven applications.

## 🛠️ Tech Stack

*   **Core:** Python
*   **Framework:** LangChain, LangGraph
*   **AI Providers:** OpenAI, Google GenAI (Gemini), Groq
*   **Tools:** Tavily (Search), Jupyter (ipykernel)


## 🌟 Features

*   **Multi-Model Support:** Seamlessly switch between OpenAI, Gemini, and Groq models.
*   **Agentic Workflows:** Utilize `langgraph` to construct advanced, stateful agent behaviors.
*   **Web Searching:** Integrate `langchain-tavily` for real-time internet searches within the agent context.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. The project uses `uv` for dependency management (indicated by `uv.lock`), but you can also use standard `pip`.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd Langchain_project
    ```

2.  **Install dependencies:**
    Using `pip`:
    ```bash
    pip install -r requirements.txt
    ```
    *(Alternatively, use `uv sync` if you are using `uv`)*

3.  **Configure Environment Variables:**
    Create a `.env` file in the root directory and add your API keys:
    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    GOOGLE_API_KEY=your_google_api_key_here
    GROQ_API_KEY=your_groq_api_key_here
    TAVILY_API_KEY=your_tavily_api_key_here
    ```

## 💻 Usage

Run the main script to interact with the configured agents:

```bash
python main.py
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
