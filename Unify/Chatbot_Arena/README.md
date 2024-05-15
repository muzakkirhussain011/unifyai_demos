# Chatbot Arena

[Demo](https://github.com/Kacper-W-Kozdon/demos-Unify/assets/102428159/e5908b4e-0cd7-445d-a1ac-3086be2db5ba)

<video width="640" height="480" autoplay>
  <source src="../../../../_static/Chatbot_arena.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

A live version of the application is hosted on Streamlit, try it out yourself using the link below: 

[ChatBot Arena on Streamlit](https://llm-playground-unify.streamlit.app/)

<p align="center">
    <em>This Streamlit application provides a user interface for interacting with Unify models through chat. It allows users to select models and providers, input text, and view the conversation history with AI assistants.
</em>
</p>
<p align="center">
	<!-- Shields.io badges not used with skill icons. --><p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<a href="https://skillicons.dev">
		<img src="https://skillicons.dev/icons?i=python,docker,github,gcp">
	</a></p>


###  Overview
This Streamlit application provides a user interface for interacting with Unify models through the chat. It allows users to select models and providers, input text, and view the conversation history with two AI assistants at a time. The app collects the data on the users' assessment of the comparative models' performance and provides an easy access to the global leaderboards which can be used as a complementary form of assessment of the performance of the models.


### Motivation
The challenge project "Chatbot arena" is based on [this article](https://arxiv.org/abs/2403.04132).


### Features

- **Chat UI**: Interactive chat interface to communicate with AI assistants.
- **Endpoint from Unify**: Choose from a variety of models and providers.
- **Conversation History**: View and track the conversation history with each model.
- **Clear History**: Option to clear the conversation history for a fresh start.
- **Global Leaderboards**: The votes are saved locally and [globally](https://docs.google.com/spreadsheets/d/10QrEik70RYY_LM8RW8GGq-vZWK2e1dka6agRGtKZPHU/edit#gid=0).




### How to use the app


1. Input Unify API Key: Enter your Unify API key in the provided text input box on the sidebar.

2. Select endpoints : Choose the models and providers from the sidebar dropdown menus.

3. Start Chatting: Type your message in the chat input box and press "Enter" or click the "Send" button.

4. View Conversation History: The conversation history with the AI assistant for each model is displayed in separate containers.

5. Clear History: You can clear the conversation history by clicking the "Clear History" button.


###  Getting Started

**System Requirements:**

* **Python**
* **streamlit**
* extra: look into the `requirements.txt` and `requirements-test.txt` files


####  Easy installation

<h4>From <code>source</code> in order to use the attached Docker file.</h4>

---

## Repository and Deployment

### Setup (without Docker)

1. Clone this repository:

    ```bash
    git clone https://github.com/samthakur587/LLM_playground
    ```
2. change directory
   ```bash
   cd LLM_playground
   ```


3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Run the app
```bash
streamlit run Chatbot_arena.py
```

---
## Contributors
<p align="center">
   


| Name | GitHub Profile |
|------|----------------|
| Samunder Singh | [samthakur587](https://github.com/samthakur587) |
| Kacper Kożdoń | [Kacper-W-Kozdon](https://github.com/Kacper-W-Kozdon) |

  <a href="https://github.com{/samthakur587/LLM_playground/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=samthakur587/LLM_playground">
   </a>
</p>
---


