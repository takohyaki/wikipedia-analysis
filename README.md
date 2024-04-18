# Wikipedia Article Retrieval System

## Project Overview

This project is aimed at building a machine learning model to identify relevant Wikipedia article titles in response to user queries, using a subset of Simple Wikipedia entries from the [Hugging Face Wikipedia dataset](https://huggingface.co/datasets/wikipedia/viewer/20220301.simple). The objective is to accurately predict article titles that answer predefined questions, with the aim of maximizing the scores based on criteria provided by Ahrefs.

## Authors

- Tammie Koh
- Alan Matthew

## Notebook Structure

1. **Data Exploration and Preprocessing:** Initial analysis and preparation of the dataset for subsequent modeling.
2. **Model Experimentations:** Testing various machine learning models and configurations to find the most effective solution.
3. **Model Evaluation:** Assessing model performance and summarizing the results to determine the best approach.

The workflow is documented across four notebooks:
- `eda_part_1.ipynb`
- `wikipedia_classifier_part_2.ipynb`
- `keyword_matching_models_part_3.ipynb`
- `LLM_model_part_4.ipynb`

Additional, incomplete work:
- `semantic_models_extra.ipynb`
- `working_semantic_models_extra.ipynb`

## Setup

To install dependencies, set up a virtual environment and activate it as follows:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Deliverables

The final deliverables include a comprehensive set of Python notebooks detailing the methodologies, experiments, and evaluations carried out in this project, showcasing the application of machine learning techniques in information retrieval.