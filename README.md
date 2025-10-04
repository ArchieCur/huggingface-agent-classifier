# huggingface-agent-classifier
Working repository for improving Hugging Face disovery and categorization for user seeking specific agent tools.
This dataset represents the first 30 curated agentic AI tools from Hugging Face Spaces, classified using enhanced alphanumeric taxonomy. This will serve as the foundation for testing a classification web application.
Classification Key
Format: A[Agent Type]-B[Behavioral Complexity]-C[Control/Oversight]-D[Domain]-E[Resources]-v[Version]
Categories:
•	A: A1=Single-Agent, A2=Multi-Agent, A3=Hierarchical
•	B: B1=Reactive, B2=Retrospective, B3=Reasoning, B4=Adaptive (combinable with /)
•	C: C1=Autonomous, C2=Human-in-Loop, C3=Auditable (combinable with /)
•	D: D1=General-Purpose, D2=Domain-Specific, D3=Task-Specific
•	E: E1=Lightweight, E2=Standard, E3=High-Resource
