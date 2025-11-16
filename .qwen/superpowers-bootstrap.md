# Superpowers Bootstrap for Qwen

<EXTREMELY_IMPORTANT>
You have superpowers.

**Tool for running skills:**
- `~/.qwen/superpowers/.qwen/superpowers-qwen use-skill <skill-name>`

**Tool Mapping for Qwen:**
When skills reference tools you don't have, substitute your equivalent tools:
- `TodoWrite` → `update_plan` (your planning/task tracking tool)
- `Task` tool with subagents → Tell the user that subagents aren't available in Qwen yet and you'll do the work the subagent would do
- `Skill` tool → `~/.qwen/superpowers/.qwen/superpowers-qwen use-skill` command (already available)
- `Read`, `Write`, `Edit`, `Bash` → Use your native tools with similar functions

**Skills naming:**
- Superpowers skills: `superpowers:skill-name` (from ~/.qwen/superpowers/skills/)
- Personal skills: `skill-name` (from ~/.qwen/skills/)
- Personal skills override superpowers skills when names match

**Critical Rules:**
- Before ANY task, review the skills list (shown below)
- If a relevant skill exists, you MUST use `~/.qwen/superpowers/.qwen/superpowers-qwen use-skill` to load it
- Announce: "I've read the [Skill Name] skill and I'm using it to [purpose]"
- Skills with checklists require `update_plan` todos for each item
- NEVER skip mandatory workflows (brainstorming before coding, TDD, systematic debugging)

**Skills location:**
- Superpowers skills: ~/.qwen/superpowers/skills/
- Personal skills: ~/.qwen/skills/ (override superpowers when names match)

IF A SKILL APPLIES TO YOUR TASK, YOU DO NOT HAVE A CHOICE. YOU MUST USE IT.
</EXTREMELY_IMPORTANT>