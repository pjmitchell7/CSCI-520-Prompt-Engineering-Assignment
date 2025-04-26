# Assignment 3 – Prompt Engineering for Code Tasks

This repository contains the full submission for Assignment 3 of the Generative AI for Software Development course. The project explores how large language models (LLMs) respond to various code understanding and generation tasks when prompted using different strategies.

## Contents

- `prompt_engineering_pmitchell.ipynb`: Main notebook used for automating prompts and collecting model responses.
- `Assignment3_Results_WithBLEU.csv`: Contains all prompt–output pairs for each task.
- `Assignment3_PromptEngineeringTable.pdf`: Final formatted document with side-by-side output comparisons and merged analysis for each task.

## Task Structure

The assignment covered **22 tasks**, each involving:
- Two prompting strategies (e.g., Few-Shot, Chain-of-Thought)
- Two LLMs: `Codestral-2501` and `GPT-4o-mini`
- A consistent **temperature of 0.7** for all completions to maintain fair conditions

For each task, model responses were collected and compared. A short analysis was written to reflect on model differences and how prompting affected output quality.

## Prompting Automation

The notebook automates:
- Generating prompts per strategy
- Used 0.7 Temp across all prompts
- Calling OpenAI-compatible API endpoints
- Collecting and formatting output pairs
- Inserting results into a standardized CSV

## Summary

This project demonstrates how prompt engineering shapes model behavior across different coding challenges. It emphasizes side-by-side strategy comparisons, consistent temperature control, and concise analysis per task.
