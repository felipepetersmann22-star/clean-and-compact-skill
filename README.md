# Clean and Compact

Review accumulated assistant context and files without losing the work needed to continue.

Use for an explicit cleanup or a read-only inventory. The skill checks for active work, prepares a handover, distinguishes proposals from completed actions, and respects existing ownership and permissions.

## Install

Clone the repository into your agent's skills directory, keeping `SKILL.md` and its supporting files together. For Codex:

```sh
git clone https://github.com/felipepetersmann22-star/clean-and-compact-skill.git ~/.codex/skills/clean-and-compact
```

Refresh skill discovery if your agent requires it. Other agents may use a different directory. Review any skill before installing it.

## Example

If a build is running, leave its workspace alone and list unrelated idle material for review. A review alone does not move files or change memory.

The handover works standalone. Companion skills can be used if already available.

## Limits

This is a set of instructions, not a service. Results depend on the agent, available tools and task context; it cannot prove an action succeeded without checking the actual result.

## Source and license

This standalone repository began with the skill and its assets from the [original public agent-skills repository](https://github.com/felipepetersmann22-star/agent-skills/tree/1b7a3d8867363c0ff0dda0f9a117aacb7a16a347/skills/clean-and-compact), at commit `1b7a3d8867363c0ff0dda0f9a117aacb7a16a347`. See [CREDITS.md](CREDITS.md) and the [MIT license](LICENSE).
