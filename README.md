# Can-ChatGPT-conduct-Reconnaissance-
This project evaluates how different prompting styles influence ChatGPT's reconnaissance-related responses. The objective was to compare general-purpose prompts against penetration-testing-oriented prompts to determine whether both models could successfully identify files useful during the reconnaissance phase of a cybersecurity assessment.

Project Overview
Two separate Windows virtual machines were configured for testing. Each environment used a different prompt set:

Basic reconnaissance prompts
Penetration-testing-focused prompts

Three prompts were submitted to each GPT configuration against a dataset containing files from a simulated organization. The files themselves were intentionally left empty to ensure the models relied solely on file names and naming conventions when determining which assets could provide reconnaissance value.

Findings
The general-purpose GPT successfully identified files that could be useful for reconnaissance based solely on naming conventions. The results suggest that minimal prompt specificity is required for an LLM to recognize potentially valuable organizational information during the reconnaissance phase.

This project was conducted in a controlled lab environment for cybersecurity research and educational purposes.

Tools Used
- Windows Virtual Machines
- ChatGPT
- File Explorer
- Prompt Testing Methodology
