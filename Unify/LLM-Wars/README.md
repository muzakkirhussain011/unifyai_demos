# LLM-Wars

### Overview
**LLM Wars** is a web application built with Streamlit that sets up a dynamic competition between two Large Language Models (LLMs). The LLMs engage in a structured debate where they challenge each other by generating complex prompts, responding to those prompts, and evaluating the responses. This application demonstrates the natural language capabilities of modern AI models in an interactive competitive environment with visualizations.

### Objective
The main goal of LLM Wars is to provide a creative and educational platform for testing AI models against each other following predefined rules. It highlights the strengths and limitations of language models while presenting AI capabilities engagingly to users.

### Tech Stack
- **Streamlit**: Used for creating the web application interface that is intuitive and interactive.
- **Unify AI**: Provides the backend LLMs that power the interactions within the application. Unify's API is utilized to send prompts to the LLMs and receive their responses in real-time.

### Application Flow
1. **Initialization**: Users start by selecting two competing LLMs and one judge LLM from a predefined list of available models.
2. **Competition Cycle**:
   - **Prompt Suggestion**: LLM1 generates a challenging prompt.
   - **Response Generation**: LLM2 attempts to respond accurately to the prompt.
   - **Verification**: LLM1 verifies the correctness of LLM2's response.
   - **Judgment**: The judge LLM evaluates the interaction. If LLM2's response is deemed incorrect, LLM1 is declared the winner, and the cycle ends. Otherwise, roles are reversed, and the cycle repeats with LLM2 generating the next prompt.
3. **Visualization**: The application provides a visual representation of the ongoing interaction, scores, and decisions made by the judge LLM.

### Motivation
LLM Wars demonstrates novel LLM applications beyond common use cases by creating a competitive AI environment. This pushes the boundaries of what language models can creatively and adaptively achieve. It also serves an educational purpose demystifying AI for audiences like students and professionals.

### Key Concepts
- **Natural Language Understanding and Generation**: At the core of LLM Wars is the ability of LLMs to understand and generate human-like text, showcasing advancements in AI language models.
- **API Integration**: Demonstrates how to effectively integrate and utilize third-party APIs (Unify AI) within a Python-based application.

## Quick Demo
https://github.com/unifyai/demos/assets/43880587/aba328d2-4c9e-4cd4-a6aa-82657e806145

```
<iframe width="560" height="315" src="https://www.youtube.com/embed/9EqWBVZSaZc?si=5jc_zRQbXu4MOosj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```

## Repository and Deployment
### Access the Source Code
The source code for **LLM Wars** is part of a larger collection of demos. You can access the original source code for this specific project [here](https://github.com/leebissessar5/Unify-LLM-Wars).

### Live Application
A live version of the application is hosted on Streamlit, allowing you to interact with it immediately without the need to set up a local environment. Visit the application at: [LLM Wars on Streamlit](https://unify-llm-wars-tftznesvztdt2bwsqgub3r.streamlit.app/).

### Running Locally
To run **LLM Wars** locally, clone the repository, then open up a terminal window from this directory (where this README is located) and follow these steps:

1. **Install Dependencies**: Install the required Python libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

2. **Launch the Application**: Finally, start the application by running:
   ```bash
   streamlit run main.py
   ```

This command initiates the Streamlit server, and you should see a URL displayed in your terminal where you can access the app locally, typically at `http://localhost:8501`.

## Contributors
| Name | GitHub Profile |
|------|----------------|
| Lee Bissessar | [leebissessar](https://github.com/leebissessar5) |
| Glorry Sibomana | [WHITELOTUS0](https://github.com/WHITELOTUS0) |
| Kato Steven Mubiru | [KatoStevenMubiru](https://github.com/KatoStevenMubiru) |
