# AI Project Workspace

A reusable workspace for managing project context across different AI tools. Keep source material, working instructions, reusable skills, plans, deliverables, and work history together so an AI assistant can use the same project knowledge across a wide range of tasks.

This workspace is designed to be adaptable rather than tied to one model or harness. You can use it with tools such as Claude Code, Cowork, OpenAI Codex, VS Code-based assistants, Amazon Kiro, or another AI tool that can access the project files. Each tool handles repository instructions and reusable skills differently, so check its setup requirements instead of assuming it will automatically load every file.

## What This Workspace Is For

Use the repository as a home for project context and work, whether the task involves research, writing, analysis, coding, document preparation, or another kind of project. The files provide a consistent place to find the inputs and guidance an AI tool needs, and to keep the resulting work organized.

## Repository Layout

```text
.
├── AGENTS.md                 # Shared repository guidance for compatible agents
├── CLAUDE.md                 # Kept aligned with AGENTS.md for Claude tools
├── context/                  # Source material, references, notes, and examples
├── outputs/                  # Deliverables created during work
├── skills/                   # Reusable task-specific guidance
├── logs/                     # Prompt history and concise work summaries
├── tasks/                    # Active and upcoming implementation plans
│   └── implemented/           # Completed plans
```

## How the Pieces Work Together

- **Instructions** in `AGENTS.md` and `CLAUDE.md` describe repository-wide expectations. Keep them consistent when either changes.
- **Context** in `context/` holds material the AI should use, such as project notes, reference documents, images, and example code.
- **Skills** in `skills/` package reusable guidance for particular kinds of work. How a skill is installed or exposed depends on the AI tool.
- **Plans** in `tasks/` capture active or upcoming implementation work. Move completed plans to `tasks/implemented/`.
- **Outputs** in `outputs/` hold completed deliverables, such as reports, converted documents, and other requested files.
- **Logs** in `logs/` preserve user prompts and concise summaries of completed work for continuity.

## A Typical Workflow

1. Open the repository in the AI tool you want to use.
2. Provide the task and point the tool to relevant files in `context/`.
3. Follow applicable repository instructions and reusable skills, using the setup expected by that tool.
4. Keep plans in `tasks/` when useful, and save requested deliverables in `outputs/`.
5. Update the logs with the prompt and a short summary so future work has useful context.

The central idea is simple: **instructions and skills guide the work, context provides the inputs, tasks organize plans, outputs hold deliverables, and logs preserve continuity.**
