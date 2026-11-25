# DSH project entry

Before any task, read `CLAUDE.md`. Follow its project rules and explicitly read the files referenced by its `@...` lines; DSH does not expand Claude Code imports.

Keep this directory as the working root. The project skills are exposed through `.dsh/skills` and depend on the sibling `.claude/` scripts, references, and `project.yaml`.

Claude Code hooks and settings are not loaded automatically by DSH. Follow the selected skill and invoke its scripts directly rather than expecting Claude hook events.
