# vera-from-scratch

 Implementing vector-based random matrix adaptation from scratch.

 ## Overview

 This is a quick and dirty implementation of VeRA, a new finetuning method published last week by Qualcomm AI Research and University of Amsterdam (see paper [here](https://arxiv.org/abs/2310.11454)). In this repo, I implement the finetuning method and demonstrate the key contributions that 1) it works and 2) it uses far fewer trainable parameters than LoRA or traditional finetuning.

 ## Try it yourself
 
 To run the code:
 - clone the repo
 - open a terminal and navigate to the repo directory
 - spin up a virtual environment with venv -> `python3 -m venv venv`
 - activate the virtual environment -> `source venv/bin/activate`
- install the requirements -> `pip install -r requirements.txt`
- open up the notebook `very.ipynb` and give it a go!