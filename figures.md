Figures Directory

This folder contains all vector-quality PDF figures used in the Berard Framework manuscript.
All figures are generated programmatically using a Colab-based Python workflow to ensure full reproducibility and APS/PRD-ready formatting.

SECTION: Contents

Each file in this directory corresponds to a figure referenced in the manuscript:

fig1_combined.pdf — Stability well (A) and vacuum oscillation (B)

fig2_effective_mass.pdf — Effective mass scaling vs. resonance invariant S0

fig3_hubble_rescaling.pdf — Hubble parameter rescaling vs. BC

fig4_combined.pdf — Acceleration profiles (A) and rotation curves (B)

fig5_framework_diagram.pdf — Conceptual flow diagram of the Berard Framework

SECTION: Regenerating Figures

All figures are produced using a Colab-ready Python script located in the main repository.
To regenerate:

Open the Colab notebook.

Run the figure-generation script.

Download the resulting PDFs from /content/figures_aps/.

Replace the corresponding files in this directory.

SECTION: Integration with LaTeX

Figures are not referenced directly in the main manuscript.
Instead, all figure environments and captions are stored in the file:

figures.tex

The main RevTeX file includes them using:

\input{figures.tex}

This keeps the main .tex file clean and ensures all figures remain synchronized across versions.

SECTION: Submission Notes

For PRD/arXiv submission, include:

this entire figures/ directory

figures.tex

the main manuscript (berard-framework.tex)

bibliography files

RevTeX will automatically locate and embed the PDFs.

This directory is intentionally minimal: only final, publication-ready PDFs live here.
All generation code and workflows are documented in the main README.md.