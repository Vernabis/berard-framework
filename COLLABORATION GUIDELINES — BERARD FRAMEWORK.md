COLLABORATION GUIDELINES — BERARD FRAMEWORK

This document outlines expectations and best practices for anyone contributing to the Berard Framework project. The goal is to maintain clarity, reproducibility, and consistency across all components of the repository.

SECTION: Communication

Collaborators are encouraged to communicate clearly and directly.
Questions, proposed changes, and conceptual discussions should be documented in writing, either through email or repository issues.
The priority is maintaining a shared understanding of the framework’s goals and structure.

SECTION: Repository Structure

The repository follows a modular architecture. Contributors should respect the existing layout:

Manuscript files remain focused on scientific content.

Figures are stored only as final PDFs in the figures/ directory.

Figure environments and captions live exclusively in figures.tex.

Notes and auxiliary documentation belong in the notes/ directory.

Code for generating figures is kept separate from manuscript files.

Changes should preserve this separation of concerns.

SECTION: Coding and Figure Generation

All figures must be generated using the established Colab-based Python workflow.
Contributors should avoid introducing local-environment dependencies or ad‑hoc scripts.
Any modifications to the figure-generation code should be documented clearly and tested to ensure consistent output.

SECTION: Documentation Standards

Every nontrivial change should be accompanied by a brief note explaining:

what was changed

why it was changed

how it affects the manuscript or figures

This ensures long-term traceability and prevents confusion during revisions or peer review.

SECTION: Scientific Consistency

Contributors should maintain consistency in:

notation

variable definitions

mathematical conventions

terminology used throughout the manuscript and figures

Any proposed changes to core definitions or symbols should be discussed before implementation.

SECTION: Version Control Practices

Contributors should:

make focused commits

write clear commit messages

avoid mixing unrelated changes in a single commit

use branches for experimental or exploratory work

This keeps the project history clean and easy to follow.

SECTION: Respect for Reproducibility

Reproducibility is a central principle of the project.
Any contribution that affects figures, equations, or numerical results must include enough information for others to reproduce the outcome.

SECTION: Tone and Professionalism

The project values clarity, rigor, and constructive collaboration.
Contributors are expected to engage respectfully, prioritize scientific accuracy, and maintain the high organizational standard of the repository.