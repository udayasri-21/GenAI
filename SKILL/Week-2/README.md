Week 2 – Provider-Agnostic LLM Client
1. Objective
To build a provider-agnostic LLM client that supports both a hosted Gemini API and a local Ollama model using a common interface.
2. Technologies Used
•	Python
•	Google Gemini API
•	Ollama
•	Llama 3.2
•	VS Code
•	Python-dotenv
•	Requests
•	Unittest
3. Project Structure
Week-2/
│
├── .env
├── llm_client.py
├── main.py
├── test_client.py
├── requirements.txt
└── README.md
4. Implementation
Gemini Provider
Connects to the Gemini cloud model using an API key.
Ollama Provider
Connects to the locally installed Llama 3.2 model through the Ollama API.
Common LLM Client
Uses a common generate() method to communicate with different LLM providers.
5. Installation
Install the required Python packages:
python -m pip install -r requirements.txt
Download the local model:
ollama pull llama3.2
6. Execution
Run the main program:
python main.py
Select a provider:
Choose provider (gemini/ollama):
Enter a prompt and receive the generated response.
7. Unit Testing
Run the test file:
python -m unittest -v test_client
8. Result
Implemented a common LLM client supporting Gemini and Ollama providers. Successfully executed the local Llama 3.2 model through Python in VS Code.

