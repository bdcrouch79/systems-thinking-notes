# Workflow Pattern

\\\mermaid
flowchart LR

Trigger[Trigger Event]
Agent[AI Agent]
Planner[Task Planner]
Executor[Execution Layer]
Result[Result / Output]

Trigger --> Agent
Agent --> Planner
Planner --> Executor
Executor --> Result
Result --> Agent
\\\

Many modern automation systems follow this pattern where AI assists in planning
while deterministic systems execute tasks.
