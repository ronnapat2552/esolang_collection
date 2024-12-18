# Esolang Interpreter Collection
This repository is a collection of interpreters for esoteric programming languages (esolangs) sourced from across the internet.<br>
This repository aims to be your go-to resource for exploring and experimenting with the weird and wonderful world of esolangs.

For the full list of Esolangs consider checking the `esolang` directory.

## Creations
This repository was created to address the challenge of finding interpreters that can be easily downloaded and run offline.

## Getting Started
To get started with the interpreters in this collection:
1. Clone the repository
2. Browse the interpreters directory to find the interpreter for your desired esolang.
3. Follow the instructions in the interpreter’s directory for setup and usage.

Or some interpreter have binaries file, you can download directly.

## Guidelines
### Contribute
We welcome contributions to expand and improve this collection! You can help by:
- Add a New Interpreter
- Improve Existing Interpreters
- Improve README files
- Report Issues

### Structure
```
.
├── esolang/
│   └── esolang-name/
|       ├── interpreters/
|       |   └── interpreter-variation-name/
│       |       ├── interpreter.py
|       |       └── README.md
│       ├── examples/
│       │   ├── example1.esolang
│       │   └── example2.esolang
│       └── README.md
├── LICENSE
└── README.md
```
Each esolang has its own folder containing:
- `interpreters` directory contains variation of interpreter implementations. *May Have Original Interpreter*
- Example programs demonstrating the language.
- A README file explaining the language specifics.
  - Have a seperate README for every interpreter variations.

For the full guidelines consider checking the `GUIDELINE.md`. *Under Construction*

## License
This project is licensed under the MIT License. See the LICENSE file for details.
