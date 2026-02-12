# Session Context

## User Prompts

### Prompt 1

**ACTION REQUIRED: Spawn a subagent using the Task tool.**

Do NOT review code directly. Instead, immediately call the Task tool with:

```
Task(
  subagent_type: "general-purpose",
  description: "Reviewer checking [feature]",
  prompt: "
    Read and follow the instructions in .claude/agents/reviewer.md

    Requirements folder: 

    Your task:
    1. Read .claude/agents/reviewer.md for your role and process
    2. Read /README.md for requirements context
    3. Read any existing review-NN.md...

### Prompt 2

How can we address the two minor suggestions?

### Prompt 3

Let's apply them.

### Prompt 4

Awesome! Let's commit and push.

