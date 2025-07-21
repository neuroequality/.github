# 🧠 NeuroEquality Ecosystem Map

This document outlines the high-level architecture and relationships between the different modules, services, and AI agents in the NeuroEquality platform.

## 🔧 Core Components

- **Safe4All Core Agent**
  - Daily support bot for neurodivergent users
  - Connects to scheduling, incident reporting, reminders

- **READY Toolkit**
  - Youth interface
  - Integrated mood tracker, prompts, and logs

- **GROW / WNIT**
  - Advocacy and empowerment apps
  - Training content delivery modules

## 🧠 AI Stack

- LLMs: Claude 3, GPT-4o, Ollama (Safe4All models)
- Prompt Templates: Structured input per agent
- Retrieval: Hybrid search (vector + keyword)

## 🔁 System Flow

1. User interacts via frontend (chat/UI/forms)
2. API routes user input to correct agent/module
3. Agents return structured response (text/task/alert)
4. Logs + audit trail persist to PostgreSQL
