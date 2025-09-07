# FinancialResearcher Crew

Welcome to the **FinancialResearcher Crew** project, powered by [crewAI](https://crewai.com).  
This project sets up a **multi-agent AI system** designed to conduct **in-depth financial research** and generate **professional reports** on companies, leveraging agent collaboration and external tools.  

---

## 🚀 What Can the FinancialResearcher Do?

The FinancialResearcher Crew is built to **research and analyze companies** in a structured, automated way.  

### Capabilities:
- 📊 **Company Research**: Collects information on a company’s financial health, history, challenges, opportunities, and future outlook.  
- 📰 **News & Events Tracking**: Finds and summarizes recent news and developments relevant to the company.  
- 🔍 **Pattern & Trend Analysis**: Identifies trends from past performance and future opportunities.  
- 📝 **Report Generation**: Produces polished, professional research reports with executive summaries and structured sections.  
- ⚠️ **Disclaimer**: Reports are **for informational purposes only** and should **not be used for trading or investment decisions**.  

---

## 🛠 Tools Used
- **[Gemini](https://deepmind.google/technologies/gemini/)** → Core LLM powering research and analysis.  
- **[Serper](https://serper.dev/)** → Used for real-time internet search to gather up-to-date company information and news.  
- **crewAI Framework** → Enables multi-agent orchestration and collaboration.  

---

## 🧑‍🤝‍🧑 Agents in Your Crew

Your FinancialResearcher Crew is composed of specialized agents, each with a distinct role:

### **Researcher**
- **Role**: Senior Financial Researcher  
- **Goal**: Research the company, its news, and potential developments.  
- **Backstory**: A seasoned researcher known for finding the most relevant information and presenting it clearly.  

### **Analyst**
- **Role**: Market Analyst & Report Writer  
- **Goal**: Analyze the research data and create a structured, professional report.  
- **Backstory**: A meticulous analyst skilled at spotting trends and communicating insights effectively.  

---

## 📋 Tasks Workflow

1. **Research Task** *(done by the Researcher)*  
   - Investigates the company’s:  
     - Current status & financial health  
     - Historical performance  
     - Challenges & opportunities  
     - Recent news & events  
     - Future outlook  
   - **Output**: A structured research document.  

2. **Analysis Task** *(done by the Analyst)*  
   - Builds on the Research Task output.  
   - Produces a polished report including:  
     - Executive summary  
     - Key insights and trends  
     - Market outlook (non-trading advice)  
     - Professional formatting with clear sections  
   - **Output**: `output/report.md`  

---

## ⚙️ Installation

Ensure you have Python >=3.10 <3.14 installed.  
This project uses [UV](https://docs.astral.sh/uv/) for dependency management.

1. Install **uv** if not already installed:
   ```bash
   pip install uv
   ```

2. Navigate to your project folder and install dependencies:
   ```bash
   crewai install
   ```

---

## 🔑 Configuration

You will need both a **Gemini API key** and a **Serper API key**.  

Create a `.env` file in the project root with the following format:

```bash
MODEL=gemini/gemini-2.0-flash-001
GEMINI_API_KEY=your_gemini_api_key_here
SERPER_API_KEY=your_serper_api_key_here
```

---

## ▶️ Running the Project

From the root folder, run:

```bash
$ crewai run
```

This will execute the workflow, with agents collaborating on research and analysis.  
The final structured report will be saved in:

```
output/report.md
```

---

## 📚 Support

- [Documentation](https://docs.crewai.com)  
- [GitHub Repository](https://github.com/joaomdmoura/crewai)  
- [Discord Community](https://discord.com/invite/X4JWnZnxPb)  
- [Interactive Docs Chat](https://chatg.pt/DWjSBZn)  

---

✨ With the FinancialResearcher Crew, you can automate professional-grade financial research and analysis with ease.  
