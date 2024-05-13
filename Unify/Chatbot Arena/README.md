
# 




<p align="center">
    <h1 align="center">⚔️ Unify Chatbot Arena: Benchmarking LLMs in the Wild</h1>
</p>


https://github.com/Kacper-W-Kozdon/demos-Unify/assets/102428159/8ed6ae60-4005-4557-bc8f-154c1a4d58c7



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



##  Overview
This Streamlit application provides a user interface for interacting with Unify models through chat. It allows users to select models and providers, input text, and view the conversation history with AI assistants.

---

## Features

- **Chat UI**: Interactive chat interface to communicate with AI assistants.
- **Endpoint from Unify**: Choose from a variety of models and providers.
- **Conversation History**: View and track the conversation history with each model.
- **Clear History**: Option to clear the conversation history for a fresh start.


---
## Usage


1. Input Unify API Key: Enter your Unify API key in the provided text input box on the sidebar.

2. Select endpoints : Choose the models and providers from the sidebar dropdown menus.

3. Start Chatting: Type your message in the chat input box and press "Enter" or click the "Send" button.

4. View Conversation History: The conversation history with the AI assistant for each model is displayed in separate containers.

5. Clear History: You can clear the conversation history by clicking the "Clear History" button.

---

##  Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

###  Installation

<h4>From <code>source</code></h4>

## Setup

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

###  Usage
```bash
streamlit run Chatbot_arena.py
```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```
---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`


---
## Contributors
<p align="center">
   <a href="https://github.com{/samthakur587/LLM_playground/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=samthakur587/LLM_playground">
   </a>

| Name | GitHub Profile |
|------|----------------|
| Samunder Singh | [leebissessar](https://github.com/samthakur587) |
| Kacper Kożdoń | [WHITELOTUS0](https://github.com/Kacper-W-Kozdon) |

---
## Used the Unify streaming API
```python
  from unify import AsyncUnify
  import os
  import asyncio
  async_unify = AsyncUnify(
     # This is the default and optional to include.
     api_key=os.environ.get("UNIFY_KEY"),
     endpoint="llama-2-13b-chat@anyscale"
  )
async def main():
   responses = await async_unify.generate(user_prompt="Hello Llama! Who was Isaac Newton?")

asyncio.run(main())
```

