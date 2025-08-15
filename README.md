## Introduction

This repository was just for me to track some of my self-directed learning. My interest grew towards a groundbreaking research paper - "Attention Is All You Need." Hence in my first iteration, I explored the architecture that built ChatGPT and many other LLMS - Transformers. Thanks to this video by Andrej Karpathy [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY), I was able to understand the Transformer architecture much better. This was quite a good course to start on learning LLMs, and I highly reccomend it for anyone interested in LLMs.


## Repository

You can find the following files:

`input.txt` for the dataset. A Shakespearean corpus. `more.txt` is supplementary, but not used at the moment.
`tiny-gpt.ipynb` for the initial data exploration and modelling. 
`bigram.py` for the simple Bigram model, a statisical language model
`v2.py` basically implements the Transformer architecture and config. Include hyperparameters that were friendly to my laptop.

## Takeaways

- Picked up the Pytorch library
- Tokenization and embeddings from scratch
- Matrix multiplication and linear algebra involved in manipulating vector embeddings
- Learnt about the various types of attention and how it is used
- Learnt about simple Bigram model >> single head attention >> multi head attention >> Transformer block, Feed-forward mechanisms, residual connections, layer normalisations, and many more to optimise the model.
- Understood the structure of a Transformer.
- The use of Softmax and ReLU activation functions in building Transformers

## Credit/Disclaimer

Code in this repository is mainly from Andrej Karpathy's video, and is not mine. I only typed it out and followed the tutorial for learning purposes. All credits go to Andrej Karpathy and also the researchers behind the paper. 

# References
Vaswani, A., Shazeer, N., Parmar, N., et al. (2017) Attention Is All You Need. arXiv: 1706.03762.
