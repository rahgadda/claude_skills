# Anthropic Skills Framework

## Overview
- Skills are folders of instructions, scripts, and resources that LLM loads dynamically to improve performance on specialized tasks. 
- This works as an orchestrator tool, enabling llms to complete specific tasks in a repeatable.
- How they work
  - LLM will not load all the skills into context, it only loads one at a time based on it relavenace.
  - When one execution is complete, it reviews available Skills, loads relevant ones, and applies their instructions.  
- Differentiation Factor
  - MCP
    - MCP connects LLM to external services and data sources. 
    - Skills on the other hand provide procedural knowledge—instructions for how to complete specific tasks or workflows.
    - You can use both together.
  - Projects
    - Projects provide static background knowledge that's always loaded when you start chats within them.
    - Skills provide specialized procedures that activate dynamically when needed and work everywhere across llm.
  - Custom Instructions
    - Custom instructions apply broadly to all your conversations.
    - Skills are task-specific and only load when relevant, making them better for specialized workflows.
