# Chatbots with LangGraph

A multi-agent chatbot system built using Langgraph that enables stateful communication between different AI agents. The project demonstrates how to create sophisticated chatbot workflows where multiple specialized agents can collaborate and communicate with each other.

# Key Features

**Core Capabilities:**

• Stateful multi-actor application using LLMs for agent creation.
• Cycle controllability and persistence for managing agent workflows.
• Integration with external tools like Wikipedia search and vector databases.
• Support for both simple chatbots and complex multi-agent systems.

**Technical Components:**

• Graph-based architecture for managing agent states and relationships.
• Flexible agent coordination and communication protocols.
• Integration with various LLM models through Grok API.
• Vector database integration using AstraDB for enhanced knowledge retrieval.


# Implementation Details
The project showcases three main implementations:

• Basic stateful chatbot using Langgraph.
• Chatbot with external tool integration.
• End-to-end RAG (Retrieval Augmented Generation) system with multiple AI agents.

The architecture uses a graph-based approach where nodes represent different agents and edges define their communication patterns, allowing for complex but controllable agent interactions.
