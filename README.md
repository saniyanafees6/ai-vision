# AI Vision

This is a shared repository between [Rissalat Ahmed](https://github.com/rkapdi) and [Saniya Nafees](https://github.com/saniyanafees6). Our goal here is to create a fullstack web application with payment integration. 

## Our Idea
*more stuff to come*
* User uploads the image
* We generate an image caption, which becomes an input to GPT2
* GPT2 generates text based on the input received from the image caption



## Dependancies 
* Python 3.6
* Torch
* Torchvision
* Scipy Version 1.1.0

## Pretrained Model and Word Map
From Sagar Vinodbabu's [repository](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning) I found this great [pretrained model with wordmap](https://drive.google.com/drive/folders/189VY65I_n4RTpQnmLGj7IzVnOF6dmePC)

## Getting Started
Ideally you would create this environment in a fresh anaconda virtual environment
1. Install the dependancies, pretrained model and word map
2. Clone the repo

`git clone https://github.com/saniyanafees6/ai-vision.git`
3. Open Terminal in the folder and enter the following command:

`python -W ignore caption.py --img='/path/to/image.jpg' --model='path/to/BEST_checkpoint_coco_5_cap_per_img_5_min_word_freq.pth.tar' --word_map='path/to/WORDMAP_coco_5_cap_per_img_5_min_word_freq.json' --beam_size=5`
4. *more steps to come*

## Credits
### Github Repositories
* [Sagar Vinodababu](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning)
* [Rishabh Anand](https://github.com/rish-16/gpt2client)

### Research Papers
* [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
* [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/pdf/1411.4555.pdf)
