# FHIR Resource Generation README

## Overview

This repository focuses on leveraging Large Language Models (LLMs), specifically OpenAI's GPT-3.5 and Anthropic's Claude, to convert unstructured free-text entries into structured MedicationStatements compliant with Fast Healthcare Interoperability Resources (FHIR). The process involves selecting and processing snippets from the MIMIC-III dataset to guide the LLMs through structured prompts. These prompts are designed to facilitate the generation of FHIR templates in .JSON format, with a specific emphasis on capturing medication ingredients and dose forms accurately.

## Prompt Structure

The prompts used in this project include:
   - Task instructions for generating components of the MedicationIngredient resource.
   - Examples of expected output in FHIR .JSON format.
   - Transformation examples.
   - A list of codes for the LLMs to select from.
   - Input text snippets to be transformed.


## Files

- **prompt1.txt**: Prompt for generating components of the MedicationIngredient resource.
- **prompt_dose.txt**: Prompt for generating components of the DoseForm resource.
- **Prompt_Engineering.ipynb**: Python notebook for executing LLMs and generating FHIR resources.



