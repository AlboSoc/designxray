# Design X-Ray

**Design X-Ray** is a structured way to look through an ordinary object's familiar appearance and expose the hidden engineering and design decisions that made it what it is.

It is intended for photographs of objects, products, furniture, interiors, public infrastructure, mechanisms, interfaces, and other designed systems. Rather than merely naming visible features, it asks what each feature is doing, what shaped it, how it may fail, and what further ideas it suggests.

The core mnemonic is **PPPP**:

- **Purpose** — What is this feature or system trying to accomplish?
- **Pressures** — What forces, constraints, incentives, materials, habits, regulations, costs, or manufacturing processes shaped it?
- **Perils** — How can it fail, frustrate, mislead, wear out, create hazards, or produce unintended consequences?
- **Possibilities** — What alternatives, improvements, repurposings, experiments, or transferable principles does it suggest?

## Why it is useful

Familiar objects become perceptually compressed: once we recognise “a chair” or “a pub interior”, we tend to stop seeing the decisions embodied in it. Design X-Ray deliberately reverses that compression. It selects details that are easy to overlook, reconstructs plausible design logic, and then looks across details for larger patterns.

The aim is not to claim privileged knowledge of the original designer's intent. Good analyses distinguish direct observation from inference and speculation.

## Typical use

Give the analyst or agent an image and ask:

> Apply Design X-Ray to this image.

A strong response should:

1. State what is visibly present before interpreting it.
2. Select several informative objects, features, interfaces, or spatial arrangements.
3. Analyse each using Purpose, Pressures, Perils, and Possibilities.
4. Separate observation, inference, and speculation.
5. End with cross-object deductions: recurring design strategies, tensions, trade-offs, or principles.
6. Summarise the overall design logic in one compact sentence.

## Repository layout

- `skill/SKILL.md` — agent-facing skill definition.
- `skill/references/method.md` — detailed PPPP method and reasoning discipline.
- `skill/references/output-format.md` — recommended response structure.
- `skill/examples/pub-interior.md` — illustrative worked example.
- `ROADMAP.md` — possible future development.
- `CONTRIBUTING.md` — guidance for extending the method and examples.

## Status

This repository is an initial specification and portable skill source. The `skill/` directory is deliberately self-contained so it can be adapted to platforms that support Agent Skills or comparable reusable instruction packages.
