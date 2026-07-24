# Assignment 4 - Python Statistics Walkthrough

This repository contains a Jupyter notebook that walks through statistical analysis in Python, based on exercises from the SciPy Lecture Notes. The goal is to practice applying common statistical and plotting techniques that will be useful in future data analysis labs.

## Source
Tutorial followed:
https://scipy-lectures.org/packages/statistics/index.html

## Contents
```
Assignment4-Stats-Scripts/
+-- notebooks/
|   +-- stats_python.ipynb  # Notebook with completed exercises and comments
+-- ai/
|   +-- stats_python.ipynb      # AI-generated statistical analysis
|   +-- stats_extension.ipynb   # AI extension: bootstrap confidence intervals
|   +-- PROMPTS.md              # Prompts used for AI generation
+-- environment.yml  # Conda environment definition
+-- .gitignore
+-- README.md        # This file
+-- REFLECTION.md    # Assignment reflection
```

## Getting Started

### Clone the Repository
```
git clone https://github.com/your-username/Assignment4-Stats-Scripts.git
cd Assignment4-Stats-Scripts
```

### Create the Conda Environment
```
conda env create -f environment.yml
conda activate stats-env
```

### Launch Jupyter Lab
```
jupyter lab
```

Then navigate to and open `notebooks/stats_python.ipynb`.

## Notes
- Each code block from the SciPy tutorial is placed in its own notebook cell.
- Detailed comments are included for every code example.
- Markdown cells are used to structure and explain each section.
- The AI version in the ai/ folder was generated using prompt-driven development (see ai/PROMPTS.md).
- The AI extension (ai/stats_extension.ipynb) demonstrates bootstrap confidence intervals, a method not covered in the tutorial.

## License
This repository is intended for educational use only.

## Acknowledgments
Based on exercises from:
https://scipy-lectures.org/packages/statistics/index.html
