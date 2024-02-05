# GPT2-Review + SAE


The goal of this project is to gain a deep intuition for the transformers architecture and brush off any rust I might have had with pytorch.

I am using Neel Nanda's collab template in order to do this. I found this when reading through Neel Nanda's article, steps on getting up to speed with Mechanistic Interpretability: https://www.neelnanda.io/mechanistic-interpretability/getting-started.

Here are the resources I used to reason through this task:
* https://arxiv.org/abs/1706.03762
* https://jalammar.github.io/illustrated-gpt2/


After completing this I feel like I not only have a better intuition when it comes to attention but I also have more familiarity with using einops notation for tensor operations. 

In addition, the last section about sampling techniques was helpful as it shows just how potentially unreliable and dependent on the last token the autoregressive nature of this model is.

## SAE

I now have decided to learn more about auto-encoders, motivated by the breakthrough research that anthropic has done to create features containing groups of activations instead of trying to decode individual neurons. Here is a link to their paper (https://www.anthropic.com/news/towards-monosemanticity-decomposing-language-models-with-dictionary-learning).

Many thanks again to Neel Nanda, who has provided a great tutorial for this as well in the colab I will be using for exercises.
