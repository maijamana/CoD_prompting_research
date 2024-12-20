# Chain of Density prompting research
**Based on the research**: From Sparse to Dense. GPT-4 Summarization with Chain of Density Prompting (https://arxiv.org/pdf/2309.04269), working on determining the effectiveness of each step of the CoD prompting approach. 

Chain of Density (CoD) is a technique designed to enhance the summarization abilities of large language models like GPT-4. By regulating the density of information in the generated summary, CoD aims to create well-balanced summaries that effectively capture the essence of complex content. Through specially crafted prompts, the AI model is guided to include crucial points while filtering out extraneous details, ensuring a clear and concise understanding of the original material.

![image](https://github.com/user-attachments/assets/cef4a7fb-f6a5-4080-be76-3d8242f566c6)
Figure 1: The Chain of Density process using an example (From Sparse to Dense: GPT-4 Summarization with Chain of Density Prompting) 

## Summarizing Examples

<img src="data/5323551520773497152.jpg" width="800">

## Structure
- **CoD_prompting_research.ipynb**: A Jupyter notebook demonstrating the text summarizing algorithm in practice.
- **data**: Medium articles with text content, title, publication date, and tags from [190k+ Medium Articles](https://www.kaggle.com/datasets/fabiochiusano/medium-articles).

## Setup Environment

To set up the environment, run the following commands:

```bash
pip install -r requirements.txt
