# wyn-humanize

Make writing shorter, clearer, and more natural while keeping your meaning and voice.

## When to use it

- An AI-generated draft sounds generic or unnatural.
- An email, post, or document is too long or repeats itself.
- A slide or headline needs fewer words.
- You need presentation headlines and H1 headings kept to a maximum of 8 words.
- You want to know what needs fixing before rewriting.

## Install with your agent

Give your agent this repository's URL and ask it to install **wyn-humanize**. The agent can handle the setup for you.

For example:

> Install wyn-humanize from https://github.com/wynwithus/wyn-humanize as a reusable skill for my assistant.

### Instructions for agents

If the user has asked you to install this skill, **perform the installation** using [INSTALL.md](INSTALL.md). The skill is at the repository root: `SKILL.md` and its supporting files belong in one `wyn-humanize/` skill folder. Use your host's skill installer or skills directory, verify the installed files, and tell the user where the skill was installed and how to use it.

### Install from a terminal

If you use the [Skills CLI](https://github.com/vercel-labs/skills), run:

```bash
npx skills add wynwithus/wyn-humanize --skill wyn-humanize
```

Choose your assistant and installation scope when prompted. Add `--global` for an installation available across projects. This optional method requires Node.js 22.20 or later; an agent can also use its own installer.

## Manual setup

Download or clone this repository and place its files in a `wyn-humanize/` folder in your assistant's skills directory. Keep `SKILL.md`, `eval.md`, `LICENSE`, and `TERMS.md` together. See [INSTALL.md](INSTALL.md) for agent setup steps.

If your chat cannot install skills, attach `SKILL.md` and `eval.md` and explicitly ask it to follow them for that conversation.

## How to use it

After installation, share your draft and say:

> Use wyn-humanize to clean this up. Return only the edited text.

For a review without rewriting:

> Use wyn-humanize to show me what needs fixing. Don't rewrite it yet.

Include any word limits you want it to follow. Checking titles and choices with a separate reader requires an assistant that can run subagents.

## Credit

Built by Nick Cybela, inspired by and built off [Peter Yang’s No AI Slop](https://github.com/petergyang/no-ai-slop).

## Rights and attribution

You may **fork, improve, reuse, and share** WYN Humanize, including commercially, under the [MIT License](LICENSE).

**You must credit Nick Cybela** by retaining his copyright notice and the full MIT permission notice in all copies or substantial portions of the skill, including modified versions. Keep other applicable copyright notices too. See [TERMS.md](TERMS.md) for the reuse and attribution details.
