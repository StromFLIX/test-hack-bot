# Building Agents: Lessons Learned from Real Implementation

> Source: https://share.google/VVvJz4TK0c2KTBxAB

#topic:artificial_intelligence, #topic:software_engineering, #topic:agent_architecture, #topic:machine_learning, #topic:developer_tools
#sentiment:neutral
#people:amp, #people:anthropic, #people:openai, #people:vercel, #people:pydantic, #people:gemini, #people:claude

The author shares practical insights from building AI agents, emphasizing that the process remains messy despite advances. Key learnings include avoiding high-level SDK abstractions in favor of direct platform SDKs for better control, implementing explicit cache management (particularly with Anthropic), and leveraging reinforcement throughout the agent loop. The piece discusses architectural decisions like using virtual file systems for shared state, challenges with output tooling and tone control, and model selection strategies. The author highlights that Anthropic's Sonnet and Haiku remain the best tool callers, while testing and evaluations continue to be the hardest unsolved problem in agent development.

---
