**View the full project: https://b-rengel.github.io/modelling_institutional_narrative_change/**

# Modelling Institutional Narrative Change (Synthetic Agent-Based Model)

This repository contains a small, self-contained learning project exploring how simple text-derived features (sentiment and emotion) can be translated into a stylised agent-based model (ABM) of narrative change within an organisation. Specifically, it models a fictional scenario of an organisation aiming to create anti-racist culture change.

The project uses a fully synthetic text corpus and a deliberately simplified modelling framework. It is intended as a learning exercise to build familiarity with text-as-data approaches, networked social influence, and agent-based modelling rather than as a realistic or predictive model of institutional change.

Linked above is a HTML notebook which walks step-by-step through the construction of the corpus, extraction of agent parameters from text, and the simulation of narrative dynamics under different intervention scenarios.

---

## Contents

- `modelling_institutional_narrative_change.Rmd`  
  Full reproducible R Markdown notebook containing code, explanations, and results.

- `docs/index.html`  
  Rendered HTML version of the notebook (viewable via GitHub Pages and linked at the top of this README).

- `docs/corpus.csv`  
  Synthetic text corpus created solely for this project.

---

## Overview of the approach

The notebook demonstrates the following:

1. Construction of a **synthetic organisational text corpus** representing different narrative positions.
2. Use of **lexicon-based sentiment and emotion analysis** to extract simple, interpretable textual features.
3. Translation of these features into **behavioural agent parameters** (e.g. openness, rigidity, voice strength).
4. Simulation of **social influence dynamics** on a small-world network.
5. Exploration of **comms-style interventions** (e.g. leadership communications) and their effects on narrative convergence over time.

All modelling choices are intentionally simple and are discussed alongside their limitations.

---

## Navigating the notebook

The HTML notebook is written as a self-contained walkthrough and can be read sequentially.  

If you wish to jump directly to particular sections:

- **Text-as-data features:** go to "Text analysis", particularly “Sentiment analysis” or “Emotion coding”.
- **ABM model logic:** see "Defining model logic" for explanation and see "Creating a function" to view the function that runs the model. 
- **Network structure:** go to “Interaction network”
- **Intervention scenarios:** go to "Running the model", specifically “Scenario 1” and “Scenario 2”

---

## Notes and limitations

- All data used in this project are **synthetic** and created solely for learning purposes.
- This project **does not** represent any real persons, organisations, policies, or institutional structures. 
- The ABM is **highly simplified** and omits many features common in applied ABMs (e.g. heterogeneous influence, cognitive biases, multi-layer networks).
- The project is **not intended to make empirical or policy claims** about real organisations.

---

## Reproducibility

The analysis can be reproduced by cloning the repository and knitting the R Markdown file.  
All required data are included in the repository, and no external APIs or credentials are needed.

---

## Status

This project represents an early-stage learning exercise and a snapshot of ongoing skill development in computational social science methods. I may add to this project in the future as my skills develop and as I explore different approaches. 

