# Final Check

`final-check` is an Agent Skill for the final engineering audit before an implementation is declared complete. It compares the original request, the implementation, the actual tests run, and anything still unverified.

## Install from this repository

Give your coding agent this repository URL and ask it to install the global `final-check` skill from `skills/final-check`.

For Codex, you can use:

```text
$skill-installer https://github.com/MahanManouchehri/final-check/tree/main/skills/final-check
```

Or paste this prompt into ChatGPT, Codex, or Claude Code:

```text
Install the global Agent Skill at https://github.com/MahanManouchehri/final-check/tree/main/skills/final-check as `final-check`. Preserve the included SKILL.md and make it available across my projects using your platform's supported user-level skill location.
```

After installation, invoke it explicitly as `final-check` or ask for a final verification after a substantial implementation task.

## Contents

- `skills/final-check/` — the portable Agent Skill.
- `plugin.json` and `.codex-plugin/plugin.json` — plugin metadata for ChatGPT and Codex-compatible distribution.

## License

MIT. See [LICENSE](LICENSE).
