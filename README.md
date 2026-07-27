# glaf4-skill-set

AI IDE plugin marketplace index for GLAF4, covering Claude Code and OpenAI Codex.

This repository contains only the marketplace manifests — plugin implementations live in their own repositories.

## Add this marketplace

| Platform | Command |
| --- | --- |
| Claude Code | `/plugin marketplace add D00000-Archt/glaf4-skill-set` |
| OpenAI Codex | `codex plugin marketplace add D00000-Archt/glaf4-skill-set` |

## Plugins

| Plugin | Version | Source | Claude Code | Codex |
| --- | --- | --- | --- | --- |
| glaf4-test | 0.2.2 | `ifoohoo/glaf4-test` | ✓ | ✓ |

After adding the marketplace, install plugins with your platform's plugin manager (e.g. `/plugin install glaf4-test@glaf4-skill-set` in Claude Code).

## English Summary

**glaf4-skill-set** is the public marketplace index of GLAF4 AI IDE plugin/skill packages, targeting Claude Code and OpenAI Codex.

- Add the marketplace with the commands above, then install individual plugins through each platform's plugin manager.
- Currently distributed: `glaf4-test`. See the table for per-platform availability.
- Each plugin's version authority lives in its own repository (self-contained manifests and git tags); this index only references them.
- Licensed under MIT — see [LICENSE](LICENSE).
