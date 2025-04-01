# Prompt Robustness Testing for Code-Generating LLMs

This repo contains the experimental artifacts for our IEEE AI Test 2025 short paper:  
**"Investigating Prompt Robustness in Code-Generating Large Language Models: An Empirical Study Across Diverse Prompt Categories"**

## 📌 Overview

We test the robustness of 3 popular LLMs (ChatGPT, Claude, Gemini) in code generation across 5 tasks and 4 prompt types (Baseline, Ambiguous, Negated, Contradictory).

## 🧪 Prompt Tasks

- Bubble Sort
- Login Validation
- File Reader
- Unit Testing
- Bank Account System

Full prompts: [prompts/](prompts/)

## 🤖 Models Evaluated

| Model     | Version Used |
|-----------|---------------|
| ChatGPT   | GPT-4o |
| Gemini    | Gemini 2.0 Flash |
| Claude    | Claude 3.7 Sonnet |

## 📊 Results

Quantitative scores + qualitative notes are in [evaluation/evaluation_results.csv](evaluation/evaluation_results.csv).

## 📁 Paper

The abstract of the IEEE short paper is in [paper/](paper/).

**Authors**:
- Sunisha Arora
University of St. Thomas, St. Paul, MN, USA  
sunisha.arora1309@gmail.com  

- Bicky Sharma
University of St. Thomas, St. Paul, MN, USA  
bickysharma063@gmail.com  

## 📄 License

MIT License
