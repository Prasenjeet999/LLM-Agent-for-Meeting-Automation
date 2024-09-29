# LLM Agent for Meeting Automation

## Overview
This project demonstrates an LLM-powered agent designed to automate meeting-related workflows. By leveraging NLP and Generative AI, the agent can handle tasks such as client information retrieval, project proposal generation, and meeting summarization, thereby reducing manual effort and enhancing productivity.

### Key Features
- **Client Information Extraction**: Automatically gathers relevant client data for better meeting preparation.
- **Project Proposal Generation**: Generates project proposals based on the context of the meeting.
- **Meeting Summarization**: Summarizes meeting discussions, highlights key points, and prepares action items.

## Workflow

### Flow Diagram
The following diagram illustrates the process flow of the LLM agent:

```mermaid
graph TD
    A[User Input] -->|1. Request Client Info| B[LLM Agent]
    B --> |2. Extracted Information| C[Client Summary]
    A --> |3. Request Proposal| D[LLM Agent]
    D --> |4. Generated Proposal| E[Project Proposal Document]
    A --> |5. Meeting Summary Request| F[LLM Agent]
    F --> |6. Meeting Summary| G[Summary Report]
