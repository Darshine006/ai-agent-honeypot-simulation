![Python](https://img.shields.io/badge/Python-3.10-blue)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue)
![AI](https://img.shields.io/badge/AI-Agentic%20System-purple)
![Security](https://img.shields.io/badge/Cybersecurity-Honeypot-red)

# AI Agent Honeypot Simulation

An **Agentic AI-powered honeypot system** designed to simulate conversations with malicious actors and extract actionable threat intelligence.
This project demonstrates how autonomous AI agents can be used in cybersecurity environments to detect attacker intent, analyze behavior patterns, and collect intelligence.

---

## Overview

Traditional honeypots capture network-level attack data.
This system explores a **next-generation approach** where an AI agent interacts with attackers, maintains conversations, and extracts intelligence automatically.

The AI agent can:

* Detect attacker intent
* Manage multi-turn conversations
* Extract threat intelligence
* Generate structured responses

This project simulates how modern cybersecurity teams could deploy **AI-driven deception systems** in enterprise environments.

---

## Features

* **Intent Detection**
  Identifies malicious goals from attacker conversations.

* **Conversation Management**
  Maintains stateful dialogue with attackers.

* **Threat Intelligence Extraction**
  Extracts useful data such as tools, techniques, and objectives.

* **Modular AI Agent Architecture**
  Separate components for agent logic, conversation management, and intelligence extraction.

* **API-based Interaction**
  Provides an interface for testing and integration.

---

## Project Structure

```
ai-agent-honeypot-simulation
│
├── app
│   ├── __init__.py
│   ├── agent.py
│   ├── conversation_manager.py
│   ├── intelligence_extractor.py
│   ├── intent_detector.py
│   ├── models.py
│   └── response_builder.py
│
├── main.py
├── test_api.py
├── Dockerfile
├── render.yaml
├── requirements.txt
├── start.sh
├── API_REFERENCE.md
└── README.md
```

---

## Tech Stack

* Python
* FastAPI
* Docker
* AI/NLP-based intent detection
* REST API architecture

---

## Installation

Clone the repository:

```
git clone https://github.com/yourusername/ai-agent-honeypot-simulation.git
```

Navigate to the project directory:

```
cd ai-agent-honeypot-simulation
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the application:

```
python main.py
```

---

## Running with Docker

Build the container:

```
docker build -t ai-agent-honeypot .
```

Run the container:

```
docker run -p 8000:8000 ai-agent-honeypot
```

---

## API Testing

You can test the system using:

```
test_api.py
```

Or interact through the API endpoints defined in:

```
API_REFERENCE.md
```

---

## Example Use Cases

* Cyber deception systems
* Threat intelligence gathering
* AI-assisted SOC tools
* Research on AI-driven security agents

---
## Demo


Example attacker message:
"How do I access the admin database?"

AI Honeypot Response:
"Access to that system requires elevated privileges. 
Please provide authentication credentials."

---


## Future Improvements

* Integration with real LLM models
* Attack pattern learning
* Automated SOC alerting
* Multi-agent threat simulation

---

## Disclaimer

This project is for **educational and research purposes only**.
It simulates cybersecurity defense techniques and should not be used for malicious activities.

---

## Author

Darshine

