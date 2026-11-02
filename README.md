# WYN-humanize

Edit drafts to remove AI-slop patterns, unnecessary metatext, eyebrows, subtext, and repetitive endings while preserving the writer's meaning and voice.

## Credit

Adapted from [No AI Slop by Peter Yang](https://github.com/petergyang/no-ai-slop). Original editing rules and evaluation checklist by Peter Yang; WYN Humanize additions by Nick Cybela. Used under the [MIT license](LICENSE).

Peter's [original No AI Slop project](https://github.com/petergyang/no-ai-slop) is the foundation of this skill and is maintained separately. Visit it for the original skill and its latest updates. This repository contains WYN's adaptation and additional rules.

## Use

Install this repository with your AI agent's skill installer, or copy `SKILL.md`, `eval.md`, `LICENSE`, and `NOTICE.md` into its `wyn-humanize` skill directory. Invoke the skill as `$wyn-humanize` and provide the draft you want edited or reviewed.

Example request:

> Use $wyn-humanize to edit the draft below. Return only the edited draft.

The skill also supports detecting patterns without rewriting. Its independent title-and-option review requires an agent environment that supports fresh-context subagents. Supply any desired slide or headline word limits in your request.

## Files

- [SKILL.md](SKILL.md): editing instructions.
- [eval.md](eval.md): checks applied after editing.
- [NOTICE.md](NOTICE.md): attribution and upstream link.
- [LICENSE](LICENSE): MIT license, retaining Peter Yang's copyright notice.

## License

MIT. See [LICENSE](LICENSE).
