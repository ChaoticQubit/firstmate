# Bundled skills

Original skills authored by ChaoticQubit, shipped with this firstmate fork so anyone who clones it can install them.
They are not loaded automatically by firstmate or your agent; they live here as a shareable backup.
To use one, copy its directory into your agent's skills directory (for Claude Code, `~/.claude/skills/`).

## Included

- `linear-method` - apply the Linear Method to project tracking and product building; firstmate's project-management skill loads this.
- `to-linear-projects` - turn a product scope into one Linear project brief per area of work.
- `to-releases` - slice a broad scope into a sequence of independently shippable releases.
- `to-features` - expand a release into feature and epic specs.
- `html-explainer` - turn any document or URL into a visual, single-file interactive HTML explainer.

## Install

    cp -R skills/extras/<skill-name> ~/.claude/skills/

## External skills this fork references but does not bundle

firstmate's crew briefs and project-management skill reference a few skills and plugins authored elsewhere; install them from their own sources.

- `ponytail` and `software-practices` - coding-discipline plugins loaded by ship briefs.
- `to-issues`, `to-prd`, and `triage` - Linear publishing skills by Mat Pocock, needed only to publish tickets to a real Linear board.

## License

Authored by ChaoticQubit.
See the repository `LICENSE`.
