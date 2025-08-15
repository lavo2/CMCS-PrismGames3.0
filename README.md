# PRISM Games 3.0 Seminar - CMCS Course, University of Pisa

This repository contains materials from my **CMCS 24/25** seminar on [PRISM Games 3.0](https://www.prismmodelchecker.org/games/), focusing on **Concurrent Stochastic Games (CSGs)**, equilibria, and probabilistic verification. The Rock-Paper-Scissors (RPS) game is used as a simple case study.

## Overview
- **Slides** (`Prism games 3.pdf`): seminar slides.
- **Models** (`*.prism`): RPS models with different turn configurations.
- **Properties** (`*.props`): property specifications used in PRISM.

## How to Use
1. Install [PRISM Games 3.0](https://www.prismmodelchecker.org/games/download.php).
2. Open a `.prism` model in PRISM.
3. Load the matching `.props` file.
4. Run the model-checking queries to, for example:
   - compute **maximum win probabilities** before losing,
   - evaluate **fixed draw/win combinations**,
   - analyse **Nash equilibria** (where applicable).

## References
- [PRISM Games 3.0 Documentation](https://www.prismmodelchecker.org/games/)
