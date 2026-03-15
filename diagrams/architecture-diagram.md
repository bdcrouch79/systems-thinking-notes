# Architecture Overview

\\\mermaid
flowchart TD

User[User / Operator]
AI[AI System]
Automation[Automation Layer]
Services[External Services]

User --> AI
AI --> Automation
Automation --> Services
Services --> Automation
Automation --> AI
AI --> User
\\\

This diagram illustrates a simple feedback loop between a human operator,
an AI reasoning layer, and an automation system coordinating external services.
