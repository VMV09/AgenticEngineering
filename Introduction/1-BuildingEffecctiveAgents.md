# Introduction 

## What are Agents?
- "Agent" can be defined in several ways. Some customers define agents as fully autonomous systems that operate idependently over extended periods, using various tools to accomplish complex tasks.

- Other ue th term to describe more prescriptve implementations that fllow predefined workflows.

- Agents and agentic workflows can however be classified together under Agentic Systems. But an important architectural distinction between workflow and agents:
    - **Workflows** are systems where LLMs and tools are orchestrated trough predefined code paths
    - **Agents**, on the other hand, are systems where LLMs dynamically direct their own processes and tool usage, maintaining control over how they accomplish tasks.

- We will however explore both types of agentic system in detail.

## When (and when not) to use agents?
- When building applications with Large Language Models, we recommend finding the simplest solution possible, and only increasing complexity when needed.

- This might mean not building agentic ssems at all. Agentic systems often trade latency and cost for beteer task performance, and you should consider when this tradeoff makes sense.

- 