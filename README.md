# Machine Learning for Text Mining (SD-TSIA214) - 2023/2024

## Course Overview

This repository contains materials and resources for the course **SD-TSIA214: Machine Learning for Text Mining**, part of the **Data & Artificial Intelligence** curriculum. The course focuses on advanced machine learning methods and natural language processing (NLP) techniques for text and opinion mining. The course covers pre-processing, representation, and learning techniques for handling textual data, with practical labs to apply the concepts learned.

### Key Topics:

- Natural Language Pre-Processing: Tokenization, part-of-speech tagging, and document representation.
- Word Embedding Techniques: Methods for representing words in vector space.
- Text Clustering and Categorization: Advanced machine learning models, including deep learning, non-negative matrix factorization (NMF), hidden Markov models (HMM), etc.
- Natural Language Resources: Lexicons, WordNet, and FrameNet.

## Prerequisites

Students are expected to have:
- Machine Learning Knowledge: Completion of SD-TSIA210 (Machine Learning) or equivalent, with a solid understanding of the theoretical foundations of machine learning and basic neural networks.

## Course Structure

- **Total Hours**: 24 hours of in-person sessions (16 sessions).
- **Credits**: 2.5 ECTS
- **Evaluation**: Lab reports and final written exam.

## Instructor

- Professor Chloe Clavel
- Professor Matthieu Labeau

## Installation and Setup

For practical exercises, you will need Python, PyTorch, and Keras. Follow the instructions below to set up your environment using `conda`:

1. Install Python:
   Download and install Python with Anaconda or Miniconda from [Conda Official Site](https://docs.conda.io/en/latest/).
2. Set Up the Environment:
   Create a new conda environment with the necessary deep learning libraries:
   ```bash
   conda create -n text-mining python=3.9 numpy pandas matplotlib nltk scikit-learn spacy gensim jupyter tqdm -c conda-forge
   ```
3. Activate the Environment:
   ```bash
   conda activate text-mining
   ```
4. Launch Jupyter Notebook (if required for exercises): 
   ```bash
   jupyter notebook
   ```

This setup will allow you to work on text mining tasks, including natural language pre-processing, classification, clustering, and representation techniques.

## How to Contribute

Feel free to contribute to the repository by:
- Submitting pull requests for corrections or improvements.
- Providing additional examples or extending the projects.
