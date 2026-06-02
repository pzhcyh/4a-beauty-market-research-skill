# 4A Beauty Market Research Skill

A Codex Skill for turning ambiguous brand research requests into a structured 4A-style market, consumer, channel, competitor, positioning, and go-to-market strategy report.

It distills a reusable research workflow: market sizing, regulatory review, platform policy checks, competitor pricing, product self-analysis, positioning, slogans, claims guardrails, unit economics, and a final report suitable for website rebuild planning.

## What This Skill Is For

Use this skill when the user asks for:

- Market research before rebuilding a website or launching a DTC brand.
- Beauty, skincare, wellness, med-aesthetic, biotech beauty, or high-trust consumer product strategy.
- Competitor analysis, positioning, slogans, pain points, itch points, and channel plans.
- A consulting-style report that answers:
  - Who pays?
  - Why do they pay?
  - Why choose this brand instead of competitors?
  - What evidence supports that choice?

## Install

Copy the skill folder into your Codex skills directory:

```powershell
Copy-Item -Recurse -Force `
  ".\skill\4a-beauty-market-research" `
  "$env:USERPROFILE\.codex\skills\4a-beauty-market-research"
```

Restart or refresh Codex so the skill metadata is discovered.

## Structure

```text
skill/
  4a-beauty-market-research/
    SKILL.md
    agents/openai.yaml
    references/report-template.md
    references/source-strategy.md
```

## License

MIT
