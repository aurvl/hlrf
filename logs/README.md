# HLRF Logs - Template Directory

This `logs/` directory is a template. It is part of the HLRF framework and is not the project-specific log directory.

When a project is launched under this framework, create a `.aiact_logs/` directory at the project root and copy the same structure from this directory into it:

```text
.aiact_logs/
├── CURRENT_TASK_SUMMARY.md
├── IDEA_LEDGER.md
├── DECISION_LOG.md
└── AI_USE_LOG.md
```

The project-specific `.aiact_logs/` directory is the project's operational memory. Agents must consult it regularly, especially `CURRENT_TASK_SUMMARY.md`, and update the relevant files as the project progresses. Major steps must trigger an update of `CURRENT_TASK_SUMMARY.md`. Keep the template files unchanged in the HLRF directory; update only the copies created inside each project.


