# Graphictac Skills

This repository contains a curated Graphictac skill set for Codex.

## Included Skills

- `graphictac-brand-strategist`
- `graphictac-product-positioning-agent`
- `graphictac-seo-content-planner`
- `graphictac-landing-page-planner`
- `graphictac-social-media-planner`
- `graphictac-sales-outreach-agent`
- `graphictac-customer-objection-agent`
- `graphictac-email-sequence-agent`
- `graphictac-business-development-agent`
- `graphictac-growth-reviewer`

## Structure

Each skill lives under `skills/<skill-name>/SKILL.md`.

## Install In Codex

Copy the desired skill folders into your Codex user skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R skills/<skill-name> ~/.codex/skills/
```

Or copy all included skills at once:

```bash
mkdir -p ~/.codex/skills
cp -R skills/* ~/.codex/skills/
```

Restart Codex after installation so the new skills are loaded.

## Notes

- These skills are written for Graphictac marketing, sales, social, SEO, and business development workflows.
- The `SKILL.md` filename inside each folder is required for Codex compatibility.

