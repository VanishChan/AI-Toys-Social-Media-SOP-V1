# Social Media Skill (XHS + Douyin)

A production-ready Codex Skill for social media operations with:
- Brief-first planning
- Industry mapping from product/persona/scene
- 3-layer content mining (L1/L2/L3)
- Dual-platform output (XHS primary + Douyin adapted)
- Day1/Day2/Day7 retrospective with AI diagnosis

## What this skill solves
- Converts ad-hoc content work into a repeatable pipeline.
- Makes topic decisions evidence-driven (not intuition-driven).
- Turns good-performing content into reusable templates.

## Directory
- `SKILL.md`: core workflow and hard rules
- `agents/openai.yaml`: skill metadata
- `references/`: SOP rules, scoring, mapping, output schemas
- `templates/`: operation card, full process doc, report templates
- `examples/`: real sample outputs from one SKU run

## Quick start
1. Copy this folder into your Codex skills directory (or clone as a repo).
2. In a project, trigger this skill by name: `social-media-xhs-douyin-sop`.
3. Fill the Brief template in `references/brief-template.md`.
4. Run workflow in order:
   - Industry mapping
   - L1 evidence
   - L2 scoring
   - L3 deep-dive
   - Production package
   - Day1/Day2/Day7 retrospective

## Hard gates
- No brief -> no production.
- No category mapping -> no mining.
- No L1/L2/L3 -> no final template.
- No Day1/Day2/Day7 records -> no template promotion decision.

## Credentials note
- This skill supports online Newrank mining.
- Brief can include Newrank credentials for that run.
- Do not commit real production credentials to public repositories.
- Use environment variables or placeholder text before publishing.

## Recommended publish setup
- Repo visibility: Public (if sharing globally)
- Add screenshots in `docs/` for better onboarding
- Add release tags for major template updates (`v1.0`, `v1.1`, ...)

## License
MIT (see `LICENSE`)
