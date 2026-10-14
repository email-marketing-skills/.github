# Free email marketing skills for AI coding agents

Email Marketing Skills is an open-source collection that helps developers turn an app or website into an email marketing strategy, lifecycle flows, complete email drafts, and a runnable local preview.

Start with your existing project. The agent reads the product context, identifies a useful customer action, maps the relevant campaigns, and prepares the first one for review. Designed for SaaS founders, app developers, website builders, and small teams learning email marketing.

## Install the starter

```sh
npx skills add email-marketing-skills/email-marketing-skills --skill email-marketing
```

Then ask your coding agent:

```text
Use email-marketing to build my strategy from this project. Map the lifecycle,
write the first campaign and a 30-day calendar, and create a local preview
with synthetic recipients. Explain what remains before live sending.
```

[Browse the skill library](https://github.com/email-marketing-skills/email-marketing-skills) · [Read the beginner guide](https://saka.run/docs/email-marketing) · [Try the copy-paste prompt](https://saka.run/email-marketing)

## Choose the job you need done

| Job | Skill |
| --- | --- |
| Build the full email marketing strategy | [email-marketing](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-marketing) |
| Review an existing program | [email-marketing-audit](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-marketing-audit) |
| Grow an opted-in email list | [email-list-growth](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-list-growth) |
| Build onboarding, activation, retention, and winback flows | [email-lifecycle](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-lifecycle) |
| Write email copy, subject lines, and CTAs | [email-copywriting](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-copywriting) |
| Plan a 30-day campaign calendar | [email-calendar](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-calendar) |
| Diagnose deliverability and authentication | [email-deliverability](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-deliverability) |
| Measure campaigns and design useful experiments | [email-experiments](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/email-experiments) |
| Research prospects and draft relevant introductions | [ai-sdr](https://github.com/email-marketing-skills/email-marketing-skills/tree/main/skills/ai-sdr) |

## What are email marketing agent skills?

They are reusable Markdown instructions and supporting resources that teach a coding agent how to carry out an email marketing task. The packages use the open Agent Skills format. The installer supports agent-specific installation, including Claude Code and Codex; actual execution depends on each agent's tools and permissions.

## Are these skills free?

Yes. The collection and its optional offline preview are licensed under Apache-2.0. Your AI agent, email provider, domain, or other external services may cost money. You do not need a Saka account to use the skills.

## Can beginners use them?

Yes. Start with the main skill and your existing app. It asks for missing facts, explains the campaign choice, and produces files you can inspect. The local preview sends nothing. A live campaign needs tested delivery, recipient eligibility, and authorization.

## Can I use them for an AI SDR?

The AI SDR skill produces sourced account research and outreach drafts. It does not invent contact details or treat public emails as newsletter consent. [Saka business discovery](https://saka.run/developers) is an optional research integration; new production records use prepaid credit. Sending and reply handling require separate services.

## Where should I start?

[Install the main skill](https://github.com/email-marketing-skills/email-marketing-skills#start-with-one-skill), follow the [email marketing quickstart](https://saka.run/docs/email-marketing), or inspect the [worked SaaS example](https://github.com/email-marketing-skills/email-marketing-skills/blob/main/examples/reportnest.md). Report reproducible problems with synthetic data so the library improves from real usage.

[Source and license](https://github.com/email-marketing-skills/email-marketing-skills) · [Skills.sh directory](https://skills.sh/email-marketing-skills/email-marketing-skills) · [Saka](https://saka.run)
