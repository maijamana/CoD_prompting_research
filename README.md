# Chain of Density prompting research
Based on the research: From Sparse to Dense. GPT-4 Summarization with Chain of Density Prompting (https://arxiv.org/pdf/2309.04269), working on determining the effectiveness of each step of the CoD prompting approach. 

Chain of Density (CoD) is a technique designed to enhance the summarization abilities of large language models like GPT-4. By regulating the density of information in the generated summary, CoD aims to create well-balanced summaries that effectively capture the essence of complex content. Through specially crafted prompts, the AI model is guided to include crucial points while filtering out extraneous details, ensuring a clear and concise understanding of the original material.

![image](https://github.com/user-attachments/assets/cef4a7fb-f6a5-4080-be76-3d8242f566c6)
Figure 1: The Chain of Density process using an example (From Sparse to Dense: GPT-4 Summarization with Chain of Density Prompting) 

## Summarizing Examples

**SIFT-Brute-Force:**  
<img src="matches/BF_match_1.png" alt="SIFT-Brute-Force" width="400">

**SIFT-FLANN:**  
<img src="matches/FLANN_match_1.png" alt="SIFT-FLANN" width="400">

**RoMa:**  
<img src="matches/RoMa_match_1.png" alt="RoMa" width="400">

**Superglue:**  
<img src="matches/SuperGlue_match_1.png" alt="Superglue" width="400">


## Extraction Examples
**SIFT:**  
<img src="matches/SIFT_extraction_1.png" alt="SIFT" width="400">

**BRISK:**  
<img src="matches/BRISK_extraction_1.png" alt="BRISK" width="400">

**ORB:**  
<img src="matches/ORB_extraction_1.png" alt="ORB" width="400">

## Structure
- **algorithm.py**: Contains the core functionality for keypoint detection and image matching.
- **demo.ipynb**: A Jupyter notebook demonstrating the image matching algorithm in practice.
- **data**: Stores preprocessed satellite images from the [Deforestation in Ukraine dataset](https://www.kaggle.com/datasets/isaienkov/deforestation-in-ukraine).
- **matches**: Holds examples of matched image pairs.


## Setup Environment

To set up the environment, run the following commands:

```bash
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
pip install .
