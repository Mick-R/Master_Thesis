# Master Thesis: LLM-Based Framework for Automating Job Listing Generation and Evaluation

This repository contains the implementation, data processing scripts, and research materials for my Master's thesis at the University of Amsterdam, conducted in collaboration with MySolution.

## Project Overview

This research develops a framework for generating job listings using Large Language Models (LLMs) and evaluating their quality through an automated pipeline. The framework combines context-specific attributes and structured data to produce high-quality, contextually appropriate job listings that align with industry standards.

### Key Research Question

How should an LLM-based framework be designed to facilitate the automatic generation of high-quality, contextually appropriate job listings?


## Methodology

The research methodology consists of the following components:

1. **Identifying Quality Metrics**: Through interviews with recruitment specialists and analysis of existing job listings to establish evaluation criteria.

2. **Initial Prompt Construction**: Designing baseline prompts incorporating findings from interviews and literature on effective job listings.

3. **Evaluation Framework**: Development of both human and LLM-based evaluation pipelines using metrics identified in the interview phase.

4. **Iterative Prompt Optimization**: Continuous refinement of prompts based on evaluation feedback to improve the quality of generated job listings.

5. **Framework Validation**: Testing the framework across various job categories and industries to ensure standardized high-quality results.

## Technologies

- **Interview Processing**: Atlas.ti for interview transcription and analysis
- **Language Models**: ChatGPT-4, Claude-3.5, Qwen-72B
- **Prompt Engineering Framework**: DSPy
- **Data Processing**: Python, pandas, numpy
- **Evaluation**: Cohen's kappa and Fleiss kappa for inter-rater reliability

## Installation



## Results

The results directory contains:
- Generated job listings for different categories
- Evaluation scores from human raters and LLM-based judges
- Inter-rater reliability metrics
- Performance analysis across different job categories

## Acknowledgments
