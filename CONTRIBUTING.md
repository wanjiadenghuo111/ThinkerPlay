# Contributing to ThinkerPlay

Thank you for helping ThinkerPlay become a better playground for ideas. The best contribution is not just another demo, but a demo that makes a concept easier to see, question, and remember.

## What Makes a Good Experiment

- It has one clear concept.
- It exposes the process, not only the final result.
- It gives the viewer a small but meaningful control surface.
- It includes a short README that explains the thinking behind the visualization.
- It can be opened without a complicated setup.

## Directory Rules

Place new experiments under the closest area:

```text
playground/
├── algorithms/
├── ai/
├── math/
├── physics/
└── systems/
```

Use lowercase English slugs for folder names:

```text
playground/algorithms/sorting/
playground/math/fractal-viewer/
playground/systems/cellular-automata/
```

## Required Files

```text
experiment-name/
├── index.html
├── README.md
└── assets/
```

If the experiment grows beyond one HTML file, keep the entry file named `index.html` and add nearby source files:

```text
experiment-name/
├── index.html
├── main.js
├── styles.css
├── README.md
└── assets/
```

## README Checklist

Each experiment README should include:

- A short summary.
- The core idea being explored.
- The main interactions.
- What to observe.
- One small challenge or question.
- A link back to the project root.

Use [docs/demo-template.md](./docs/demo-template.md) as the starting point.

## Pull Request Checklist

- The experiment opens from its `index.html`.
- The project root [index.html](./index.html) links to the experiment.
- The root [README.md](./README.md) lists the experiment.
- The experiment has a README.
- File and folder names are stable, readable, and URL-friendly.
- Large generated assets are avoided unless they are necessary.

## Style Notes

- Prefer readable code over clever code.
- Keep visual controls compact and predictable.
- Use comments only where they clarify a non-obvious idea.
- Keep each experiment focused; split it when it starts teaching multiple unrelated concepts.
