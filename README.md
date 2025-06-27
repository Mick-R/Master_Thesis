# Master Thesis: LLM-Based Framework for Automating Job Listing Generation and Evaluation

This repository contains the implementation, data processing scripts, and research materials for my Master's thesis at the University of Amsterdam, conducted in collaboration with MySolution.

## Project Overview

This study develops a systematic framework for generating and evaluating job listings using Large Language Models (LLMs). The framework combines standardized information inputs, empirically derived quality metrics, and human-in-the-loop processes to produce job listings that align with expert recruitment standards.

### Key Research Question

How should an LLM-based framework be designed to facilitate the automatic generation and reliable evaluation of high-quality, contextually appropriate job listings?

## Components

The computational methodology consists of the following components:

0. **Identifying Quality Metrics**  
   Interview coding and thematic analysis to define a set of quality metrics based on recruiter expertise.

1. **Initial Prompt Construction**  
   Translating information requirements and writing guidelines into prompt components that guide LLM-based generation.

2. **Validation Experiment 1: Human Inter-Rater Agreement**  
   Implementing both human-to-human and human-to-LLM agreement pipelines using Gwet’s $AC_1$ to assess consistency and interpretability.

3. **Validation Experiment 2: Human-LLM Inter-Rater Agreement**  
    Evaluating the alignment between human expert ratings and LLM-based evaluations using GPT-4o and Claude-3.5 as independent judges. This experiment assesses whether automated evaluation can reliably      replicate expert judgment patterns while mitigating self-enhancement bias through dual-model evaluation.


## Technologies Used

- **Qualitative Analysis**: Atlas.ti for codebook generation and co-occurrence tracking  
- **LLMs**: GPT-4o, Claude 3.5 Sonnet
- **Evaluation**: Gwet’s $AC_1$, raw agreement scores, and bias metrics  
- **Tools**: Python, R, Jupyter Notebooks, pandas, numpy, openai, anthropic, langchain

## Repository Structure

```bash
.
├── 0.Interview coding/                 # Codebooks and qualitative analysis outputs
├── 1. intial prompt/                  # Prompt input/output data and prompt examples
├── 2. human_inter_rater_agreement/   # Human rating results and IRR analysis
├── 3. LLM_evaluation_pipeline/       # LLM evaluation notebooks and result logs   
├── README.md
└──  requirements.txt
