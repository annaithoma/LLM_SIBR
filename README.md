<img width="545" alt="Screenshot 2025-06-20 at 19 41 14" src="https://github.com/user-attachments/assets/69203158-f81d-4afb-ac09-d192ca250f56" />

# LLMS FOR METASCIENCE: MAPPING RESEARCH LANDSCAPES
This repository contains the workshop material for "LLMS FOR METASCIENCE: MAPPING RESEARCH LANDSCAPES" at the Summer Institute for Bounded Rationality. The workshop contains a mix of short introductory talks, discussions, and exercises.

By [Anna Thoma](https://www.mpib-berlin.mpg.de/staff/anna-thoma) and [Dirk Wulff](https://www.mpib-berlin.mpg.de/person/93374/2549). 

## Exercises
* Exercise 1: [Evaluating semantic similarity (embedding models)](https://github.com/annaithoma/LLM_SIBR/blob/main/1_embeddings_map.ipynb)
* Exercise 2: [Extracting topics](https://github.com/annaithoma/LLM_SIBR/blob/main/2_tag_extraction.ipynb)

## Installation
This instruction was written by [Zak Hussain](https://github.com/Zak-Hussain), who has other cool stuff to try out on his GitHub!

### Hugging Face and Meta Llama License
* Make sure you have a hugging Face account (https://huggingface.co/join).
* Go to the [meta-llama/Llama-3.2-1B-Instruct](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct) model page and fill in the 'COMMUNITY LICENSE AGREEMENT' form at the top of the page to get access to the model (this may take a few minutes).

### Google Colab and GitHub Repository
* If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
* Navigate to Google Drive (https://drive.google.com/).
* In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
* Copy the following code snippet into the first cell of the notebook. Run it (shift + enter or click ► button) to mount your Google Drive to the Colab environment. A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab.
```
from google.colab import drive
drive.mount("/content/drive")
```
* You will need to allow Google access to everything in your Google Drive for this to work, unfortunately. If you do not feel comfortable doing this, you can consider creating a new Google account for the purposes of this workshop.
* Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive (you can also fork the repository instead if you prefer):
```
%cd /content/drive/MyDrive
!git clone https://github.com/annaithoma/LLM_SIBR.git
```
* Go back to your Google Drive and navigate to the folder "LLM_SIBR". You should see the relevant notebooks (.ipynb files) and data (it may take a couple of minutes for the files to appear). You are now ready to work through the exercises in the course!
