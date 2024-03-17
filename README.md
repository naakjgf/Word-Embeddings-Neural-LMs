# Neural Language Models Homework

## Overview
This repository contains all necessary materials for completing the Neural Language Models (Neural LM) homework assignment. This assignment focuses on building and evaluating neural language models using Python and Jupyter Notebooks. Due to the computational requirements, some tasks in this project may take a significant amount of time to train. 

## Important Information

- **Partner Work**: This assignment is designed to be completed in pairs, although individual completion is allowed. Collaborating can provide a richer learning experience and distribute the workload more evenly.
- **Late Submissions**:
  - **With Late Passes**: If both partners have unused late passes, the assignment can be submitted late with no penalty.
  - **Single Late Pass**: If only one partner has a late pass, the submission can be up to 24 hours late without penalty.
  - **No Late Passes**: Without late passes, formal extension requests must be made in accordance with the syllabus.
  - Ensure any requests for extensions are communicated well in advance.

## Starter Files

To get started, download the following notebooks and utility files:

- **Notebooks**:
  - `neurallm_task01.ipynb`
  - `neurallm_task2.ipynb`
  - `neurallm_task3.ipynb`
  - `neurallm_task4.ipynb`

- **Utility Files**:
  - `neurallm_utils.py`

## Data Files

The following datasets are provided for training and evaluation:

- **Training Data**: `spooky_author_train.csv`
- **Example Language Model Files**:
  - `spooky_vanilla_3_word.txt`
  - `spooky_vanilla_3_char.txt`

## Submission Requirements

Your submission should include the following:

- The four completed Jupyter notebooks.
- The `neurallm_utils.py` file.
- Two text files (`char_sents.txt` and `word_sents.txt`) containing 100 generated sentences each.
- Supporting files for Task 4 evaluation, depending on the chosen option:
  - Option 1: `valid_words_lms.csv` and `invalid_words_lms.csv`
  - Option 2: Your survey data in a `.csv` file.

## Timing Information

For your reference, here are some timing benchmarks from previous runs:

- Data loading (`read_data`): 7 seconds
- Embeddings training: 31 seconds
- Generating n-gram training samples: 4 seconds
- Transforming sequence dimensions: 2 seconds
- Training times for models:
  - Word Model (5 epochs): 13 minutes and 22.65 seconds
  - Character Model (5 epochs): 12 minutes and 22.48 seconds

## Getting Started

1. Clone this repository or download the starter files.
2. Install the required Python packages. A list of required libraries can be found in `requirements.txt`.
3. Follow the instructions in each Jupyter notebook.

## Collaboration and Support

- Discuss and divide the work fairly if working in a partnership.
- Use the issue tracker for questions or if you're encountering issues.
- Regularly commit and push your work if using a shared repository to keep each other updated.

Good luck, and enjoy building your neural language models!
