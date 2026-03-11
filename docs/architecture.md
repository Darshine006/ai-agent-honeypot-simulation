# System Architecture

```mermaid
flowchart TD

A[Attacker / User] --> B[API Endpoint]
B --> C[Conversation Manager]
C --> D[Intent Detector]
C --> E[Response Builder]
D --> F[Intelligence Extractor]
F --> G[Threat Intelligence Database]
E --> H[Generated AI Response]
H --> A
```

## Explanation

1. **API Endpoint** receives attacker interaction.
2. **Conversation Manager** tracks conversation state.
3. **Intent Detector** identifies attacker goals.
4. **Intelligence Extractor** gathers threat data.
5. **Response Builder** generates the honeypot reply.
