# ThinkerPlay

**Think. Play. See.**

ThinkerPlay is a collection of interactive thinking experiments. Each experiment turns an abstract idea into something visible, playable, and worth discussing.

This repository is currently focused on single-page HTML experiments, so every demo can be opened directly in a browser. As the project grows, shared utilities and a Vite-based development workflow are prepared for richer visualizations.

## Current Experiments

| Area | Experiment | Entry |
| --- | --- | --- |
| AI | Perceptron training process | [playground/ai/perceptron](./playground/ai/perceptron/) |
| AI | Convolution kernel, feature map, and pooling | [playground/ai/cnn-kernel-pooling](./playground/ai/cnn-kernel-pooling/) |
| AI | LeNet-5 matrix convolution process | [playground/ai/lenet5-convolution](./playground/ai/lenet5-convolution/) |
| Systems | HDD 3D visualizer | [playground/systems/hdd-3d-visualizer](./playground/systems/hdd-3d-visualizer/) |

Open [index.html](./index.html) to browse the project as a local gallery.

## Quick Start

The simplest way:

```bash
# Open this file in your browser
index.html
```

For a local development server, install Node.js and npm first, then run:

```bash
npm install
npm run dev
```

Then visit the local URL printed by Vite.

## Project Map

```text
ThinkerPlay/
├── index.html
├── README.md
├── CONTRIBUTING.md
├── docs/
│   ├── demo-template.md
│   ├── philosophy.md
│   └── roadmap.md
├── shared/
│   ├── components/
│   ├── hooks/
│   └── utils/
└── playground/
    ├── algorithms/
    ├── ai/
    │   ├── cnn-kernel-pooling/
    │   ├── lenet5-convolution/
    │   └── perceptron/
    ├── math/
    ├── physics/
    └── systems/
        └── hdd-3d-visualizer/
```

## Experiment Standard

Every experiment should answer four questions:

| Question | Purpose |
| --- | --- |
| What are we thinking about? | Explain the core idea behind the demo. |
| How do we play with it? | Describe the main interactions. |
| What should we observe? | Point out the patterns that matter. |
| What is a good challenge? | Invite the reader to test an intuition. |

Recommended structure:

```text
experiment-name/
├── index.html
├── README.md
└── assets/
    └── .gitkeep
```

## Documentation

- [Design philosophy](./docs/philosophy.md)
- [Roadmap](./docs/roadmap.md)
- [Demo README template](./docs/demo-template.md)
- [Contribution guide](./CONTRIBUTING.md)

## Taglines

- Think. Play. See.
- Where Ideas Become Interactive.
- Learn by Seeing, Grow by Playing.
- Play with Code, Think with Vision.

## License

No formal open-source license has been selected yet. Before public release, choose a license such as MIT or Apache-2.0 so contributors know how they can use and share the work.
