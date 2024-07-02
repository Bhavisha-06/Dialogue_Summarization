# Dialogue Summarization with FLAN-T5

This Jupyter notebook demonstrates how to use the FLAN-T5 model for dialogue summarization using the DialogSum dataset. It covers:

1. Setting up the environment and installing required libraries
2. Loading the DialogSum dataset 
3. Loading the FLAN-T5 model and tokenizer
4. Basic tokenization and encoding/decoding examples
5. Generating summaries without prompt engineering
6. Zero-shot summarization with a simple prompt
7. One-shot and few-shot summarization examples
8. Experimenting with different generation configurations

## Key Components

- Dataset: DialogSum (from HuggingFace datasets)
- Model: google/flan-t5-base
- Libraries: transformers, datasets, torch, torchdata

## Usage

1. Install the required libraries (instructions in the notebook)
2. Run the cells in order to see examples of dialogue summarization
3. Experiment with different prompts and generation configurations

## Notes

- The notebook includes examples of baseline human summaries for comparison
- Various prompt engineering techniques are demonstrated
- Generation parameters like max_new_tokens, temperature, and do_sample are explored

This notebook serves as a starting point for experimenting with FLAN-T5 for dialogue summarization tasks. Feel free to modify prompts, try different model sizes, or apply to other summarization datasets.
