# Graph WebSearch Agent 🌐
A sophisticated web search agent built using LangGraph that leverages multiple AI models to perform intelligent web searches and provide comprehensive answers to research questions.

[![Graph WebSearch Agent Overview](https://github.com/user-attachments/assets/ecbeb807-7811-4fcb-8251-0f23c118802f)](https://www.loom.com/share/5d1c55a1670f4f5abfd6e8c6ecec89d7)

## 🌟 Features

- Multi-agent system architecture
- Support for multiple LLM providers:
  - OpenAI
  - Groq
  - Claude
  - Gemini
  - Ollama (local)
  - vLLM (custom endpoint)
- Interactive Chainlit UI
- Configurable search parameters
- Automatic web scraping and content analysis
- Intelligent result filtering and summarization

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- API keys for desired LLM providers
- Serper API key for web searches

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/graph_websearch_agent.git
cd graph_websearch_agent
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Configure your API keys in `config/config.yaml`:
```yaml
SERPER_API_KEY: "your-serper-api-key"
OPENAI_API_KEY: "your-openai-api-key"
GROQ_API_KEY: "your-groq-api-key"
CLAUD_API_KEY: "your-claude-api-key"
GEMINI_API_KEY: "your-gemini-api-key"
```
### Running the Application

#### Windows:

```powershell
.\run_windows.ps1
```

#### Linux/Mac:

```bash
./run_linux.sh
```


## 🔧 Configuration

The application can be configured through the Chainlit UI. Available settings include:

- LLM Provider selection
- Model selection
- Temperature settings
- Recursion limits
- API key management
- Custom server endpoints

## 🏗️ Architecture

The system uses a multi-agent architecture with specialized agents:

1. **Planner Agent**: Creates search strategies
2. **Selector Agent**: Chooses relevant search results
3. **Reporter Agent**: Synthesizes information
4. **Reviewer Agent**: Validates responses
5. **Router Agent**: Manages workflow between agents
6. **Final Report Agent**: Formats final output

## 📝 Usage

1. Start the application
2. Configure your settings in the UI
3. Enter your research question
4. The agent system will:
   - Plan the search strategy
   - Execute web searches
   - Analyze results
   - Provide a comprehensive answer

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- LangGraph team for the graph-based agent framework
- Chainlit team for the UI framework
- All contributors and users of this project
