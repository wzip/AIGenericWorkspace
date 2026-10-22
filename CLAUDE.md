# AGENTS.md

## Repository Expectations

- This is a general-purpose project repository for handling a wide range of everyday tasks. Use it flexibly for whatever the current task requires.
- AGENTS.md and CLAUDE.md serve the same purpose of providing global instructions for agents working on this project. The files must be identical. Any changes to one, must be made to the other.
- Store project context, examples, and example code in `context/`.
- Store outputs from work conducted in this repository in `outputs/`.
- Keep persistent project notes in `logs/`.
- Record every user prompt verbatim in `logs/promptlog.md`.
- Record completed task summaries and vital downstream-agent context in `logs/processlog.md`.
- If either log file already exists, append new entries to the end and do not alter previous content.
- Create `logs/processlog.md` and `logs/promptlog.md` if they are missing before doing project work.
- Keep log entries concise, dated, and useful for future agents continuing work in this repository.
- Relevant skills are to be kept in skills/ New skills are to be created in this folder.

## Implementation Plans

- Store new implementation plans in `tasks/` with descriptive, sequential filenames.
- Keep only active or upcoming implementation plans in the root of `tasks/`.
- Move completed implementation plans into `tasks/implemented/`.
- Create `tasks/implemented/` if it is missing before moving completed plans.
- When saving or moving implementation plans, update `logs/promptlog.md` and `logs/processlog.md` according to the logging rules above.
