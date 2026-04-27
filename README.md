# 🛠️ Technical FAQ: Nova Prime v2.4 Architecture
### Q1: Is Nova Prime a standard AI wrapper?
### Q2: Why use 20+ independent GitHub repositories as data nodes?


No. Nova Prime is a Sovereign Intelligence Framework. Unlike wrappers that handle logic in the client-side browser, Nova Prime utilizes a Decoupled Node Architecture. All tactical inference and "Friction Matrix" logic are isolated within a server-side Black Box (Cloudflare Workers), ensuring zero-client visibility of proprietary IP and API keys.

Q2: Why use 20+ independent GitHub repositories as data nodes?

To solve the latency of insight. By decentralizing the data into team-specific silos (e.g., Node 01 for Manchester United, Node 09 for Brentford), we achieve horizontal scalability. Each node operates as an independent "Intelligence Silo," allowing the system to perform high-velocity retrieval without the overhead of a monolithic database.

Q3: How is security handled in a "Zero-Client" model?

Security is engineered at the edge.

Key Isolation: API keys (BSD, Groq) are never exposed to the frontend. They are stored as encrypted environment secrets within the Cloudflare routing layer.

Prompt Protection: The system prompts that define the "Critical Vulnerability" and "Tactical Friction" modes are server-side. They cannot be reverse-engineered or scraped from the browser's network tab.

Sanitization: Every request passes through a proxy layer that validates the "Sovereign-Mode" header before inference is triggered.

Q4: What is the "Multi-Agent Workforce" orchestration?

Nova Prime was not built by a single tool, but orchestrated by a multi-agent workforce under the direction of the Lead Architect:

Governance & Security (Gemini): Directed the system roadmap and stress-tested the Black Box protocols.

UX/UI Engineering (ChatGPT): Facilitated the broadcast-grade design language and experience hierarchy.

Core Systems Implementation (Claude): Orchestrated the heavy-lift coding, secure proxy layers, and sub-second data handshakes.

Q5: What is the "Data Synchronicity" metric?

We have replaced subjective "AI Confidence Scores" with a proprietary Data Synchronicity (Heartbeat) metric. This tracks the real-time latency and sync-status between the subsidiary data nodes and the central engine. If the synchronicity falls below the broadcast threshold, the system flags the insight as "Stale," ensuring 100% tactical authority.
