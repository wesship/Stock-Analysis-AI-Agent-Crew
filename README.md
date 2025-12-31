> [!NOTE]
> This project is a fork of [parthhhx/Stock-Analysis-AI-Agent-Crew](https://github.com/parthhhx/Stock-Analysis-AI-Agent-Crew). The original project and its contributors can be found there.

# Stock Analysis AI Agent Crew

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/Stock-Analysis-AI-Agent-Crew/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/Stock-Analysis-AI-Agent-Crew/actions/workflows/ci.yml)

> Multiple LLM based AI Agents work together to gather information about stocks, process financial details and market sentiments, and provide advice on performing trades.

---

## ✨ Features

- **Multi-Agent System**: Utilizes a crew of AI agents for comprehensive stock analysis.
- **Data Gathering**: Collects stock information, financial details, and market sentiment.
- **Trade Recommendations**: Provides advice on stock trading based on the analysis.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10
- Conda (Anaconda or Miniconda)
- API keys from Serper, Groq, Browserless, and SEC-API

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wesship/Stock-Analysis-AI-Agent-Crew.git
   cd Stock-Analysis-AI-Agent-Crew
   ```
2. Create and activate a Conda environment:
   ```bash
   conda create -n stock-analysis-crew python=3.10 -y
   conda activate stock-analysis-crew
   ```
3. Install dependencies:
   ```bash
   poetry install --no-root
   ```
4. Set your API keys in a `.env` file.

### Usage

```bash
python main.py
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [CrewAI](https://www.crewai.com/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
