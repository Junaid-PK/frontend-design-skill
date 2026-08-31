# Frontend Design Skill

[![skills.sh](https://skills.sh/b/Junaid-PK/frontend-design-skill)](https://skills.sh/Junaid-PK/frontend-design-skill)

A practical agent skill for designing SaaS interfaces that feel clear, trustworthy, and ready for real users—not like decorated AI boilerplate.

Most generated frontends are technically functional. They still lose people through noisy dashboards, competing colors, repeated cards, vague actions, missing loading states, and screens that never make the next step obvious. This skill gives coding agents a concrete decision framework for fixing those problems.

## What it changes

The skill teaches an agent to begin with the user's job and design the shortest clear path to a useful result. It emphasizes:

- one primary intent and visual subject per screen;
- restrained color, consistent spacing, radii, typography, and iconography;
- compact, scannable tables, lists, cards, and action hierarchies;
- plain, consistent interface copy that tells users exactly what happens;
- realistic empty, loading, error, success, undo, and destructive states;
- progressive onboarding instead of forced product tours;
- motion that communicates state rather than decorating the page;
- SaaS landing pages built around outcomes and focused product proof;
- responsive, accessible interfaces tested with messy real-world data;
- a final simplification audit before handoff.

The result is not “minimalism at all costs.” Brand character and distinctive details are welcome when they support the product. Clarity, confidence, and task completion remain the quality bar.

## Good uses

Use this skill when asking an agent to:

- design a SaaS dashboard, web app, onboarding flow, or landing page;
- refine an existing interface that feels noisy or AI-generated;
- establish a small, coherent design system for a product;
- improve hierarchy, copy, states, navigation, or responsive behavior;
- review frontend work before launch.

Example prompts:

```text
Use the frontend-design skill to design an analytics dashboard for a small sales team.
```

```text
Use the frontend-design skill to simplify this generated SaaS UI and make the primary workflow obvious.
```

```text
Use the frontend-design skill to turn this product brief into a responsive landing page with focused product proof.
```

## Install

Install with the Skills CLI:

```bash
npx skills add Junaid-PK/frontend-design-skill
```

If the skill earns a place in your workflow, consider starring this repository—it helps other skill users discover it.

The CLI supports Codex, Claude Code, Cursor, GitHub Copilot, Windsurf, Gemini CLI, and other skill-compatible agents.

For a manual Codex installation, copy `frontend-design/` into your personal skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R frontend-design ~/.codex/skills/frontend-design
```

Restart or open a new agent session after installation so the skill catalog refreshes.

## Repository structure

```text
frontend-design-skill/
├── README.md
├── LICENSE
└── frontend-design/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```

`SKILL.md` contains the agent instructions. `agents/openai.yaml` provides optional Codex-facing display metadata. The skill has no runtime dependencies and does not require a specific frontend framework.

## Philosophy

Every screen should help someone understand, decide, or finish. If an element does none of those things, remove it.

The skill is based on practical SaaS UI lessons about restrained visual systems, consistency, progressive guidance, visible system status, ethical friction, focused product proof, and outcome-oriented interface copy. Those ideas have been distilled into an agent-ready workflow rather than copied as a visual style.

## Contributing

Issues and pull requests are welcome. Useful contributions include clearer heuristics, stronger accessibility guidance, realistic failure cases, and examples that improve how the skill generalizes across products.

## License

Apache License 2.0.
