<p align="center">
  <a href="https://wetheusers.ai"><img src="https://wetheusers.ai/media/og-card.jpg" alt="We believe there is a better way." width="760"></a>
</p>

<h1 align="center">We the Users</h1>

<p align="center"><em>An internet owned by the people who use it. A call to draft it, written in the open.</em></p>

Every search, message, and purchase is the shadow of a real life. Yours. Today a few companies own that shadow, and the value built on it flows to them. We don't think it has to be this way, so we're gathering the people who want to help write what comes next. The argument is at [wetheusers.ai](https://wetheusers.ai): six essays, a provisional Declaration of Internet Independence, and a founding brief that prints its own strongest counter-arguments.

## What is here

| Repository | What it holds |
|---|---|
| [**skill**](https://github.com/wetheusers-ai/skill) | One 33-line file for your coding agent. It keeps a copy of your work before a platform gets it, reads the terms before you agree and quotes the line it relied on, and asks for export and delete on day one of anything you build. It never puts its name in your work. |
| [**wetheusers**](https://github.com/wetheusers-ai/wetheusers) | The drafting table. The Declaration, the essays, and the founding brief, all working drafts. Pull requests and discussions are welcome on any line. |
| [**website**](https://github.com/wetheusers-ai/website) | The site and its backend, in the open. The sign-up form counts only verified emails, names are never public, and every confirmation email carries a one-click delete. |

## Start with your own agent

```
mkdir -p ~/.claude/skills/we-the-users
curl -fsSL https://wetheusers.ai/skill/SKILL.md -o ~/.claude/skills/we-the-users/SKILL.md
```

Codex and agents that share its folder use `~/.agents/skills/we-the-users/` instead. Read the file before you install it; it is short enough. Details, the always-on version for `AGENTS.md`, and the hash to check against are at [wetheusers.ai/skill](https://wetheusers.ai/skill).

## Take up the pen

Signing is the smallest edit. If you have more than a name to add, open a [discussion](https://github.com/wetheusers-ai/wetheusers/discussions) or a pull request on the [documents](https://github.com/wetheusers-ai/wetheusers). None of this is final. The final version is the one written together.

---

<p align="center"><sub>An open project, not affiliated with any company. Documents CC BY-SA 4.0, code Apache-2.0, the skill CC BY 4.0. Privacy: <a href="https://wetheusers.ai/privacy/">wetheusers.ai/privacy</a></sub></p>
