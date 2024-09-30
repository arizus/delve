# Why Does ChatGPT "Delve" So Much? Exploring the Sources of Lexical Overrepresentation in Large Language Models

This repository contains the code and data of the paper "Why Does ChatGPT “Delve” So Much? Exploring the Sources of Lexical Overrepresentation in Large Language Models".

## Abstract
Scientific English is currently undergoing rapid change, with words like "delve," "intricate," and "underscore" appearing far more frequently than just a few years ago. It is widely assumed that scientists' use of large language models (LLMs) is responsible for these trends. We use a novel method to identify 21 focal words whose increased occurrence in scientific abstracts is likely the result of LLM usage. We then pose "the puzzle of lexical overrepresentation": why are such words overused by LLMs? We fail to find evidence that lexical overrepresentation is caused by model architecture, algorithm choices, or training data. To assess whether reinforcement learning from human feedback (RLHF) contributes to the overuse of focal words, we undertake comparative model testing and conduct an exploratory online study. While the model testing is consistent with RLHF playing a role, our experimental results suggest that participants may be reacting differently to "delve" than to other focal words. We note that lack of transparency remains an obstacle to such research on the sources of lexical overrepresentation. 


## Repository Contents

- **data/**: Contains sample data. Actual data files are hundred of gigabytes big, and have to be built locally with the code in /code/get_human_data/ and /other_datasets/. 
- **code/**: Python scripts used for the extraction of focal words (brute_force_div.py and incl.ods in /analysis/), model testing (PPAID_calc_normalised_entropy_with_llama.ipynb in /analysis/), and generating AI abstracts (in /generate_ai_data/). Plots can be generated with the code in /plot/ and the code for the experimental website can be found in /website/. 

### Requirements and running the code

- Python 3.9+
- Install required packages via pip

## Citation
If you use this code or data in your research, please cite:

"`
@article{Anonymous2025,
  title={Why Does ChatGPT "Delve" So Much? Exploring the Sources of Lexical Overrepresentation in Large Language Models},
  author={Anonymous},
  journal={tbd},
  year={2025}
}
"`

## Licence
The licence of this project has yet to be determined. 

## Contact
For any questions or issues, please contact the repo owner.
