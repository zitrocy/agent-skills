# Agent Skills

Curated Korean writing and AI agent skills for staff engineers.

## Skills

[humanizer-ko](skills/humanizer-ko/SKILL.md): remove Korean AI-isms and hype.

[korean-prose](skills/korean-prose/SKILL.md): refine technical, PR and UI copy.

[prompt-optimizer](skills/prompt-optimizer/SKILL.md): constraint-first prompts.

[punchcutter](skills/punchcutter/SKILL.md): custom typeface prompt helper.

## Use

Clone the repository and copy skills into the project directory for your agent.

```sh
git clone https://github.com/zitrocy/agent-skills.git
# Claude Code
mkdir -p .claude/skills && cp -R agent-skills/skills/* .claude/skills/
# Cursor
mkdir -p .cursor/skills && cp -R agent-skills/skills/* .cursor/skills/
# Codex
mkdir -p .agents/skills && cp -R agent-skills/skills/* .agents/skills/
```

Ask the agent to use the desired skill by name and provide source material and
constraints. Discovery can vary by version; consult your agent documentation.
You can also open a SKILL.md and supply it as context manually.

Review outputs before use. Do not share confidential material without authorization.
