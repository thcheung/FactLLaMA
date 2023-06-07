# CDGTN
The official code of paper, "FactLLaMA: Optimizing Instruction-Following Language Models with External Knowledge for Automated Fact-Checking".

## Abstract

Automatic fact-checking plays a crucial role in combating the spread of misinformation. Large Language models (LLMs) and Instruction-Following variants, such as InstructGPT and Alpaca, have shown remarkable performance in various natural language processing tasks. However, their knowledge may not always be up-to-date, potentially leading to inaccuracies in fact-checking. To address this limitation, we propose combining the power of instruction-following language models with external evidence retrieval to enhance fact-checking performance. Our approach involves leveraging search engines to retrieve relevant evidence for a given input claim. This external evidence serves as valuable supplementary information to augment the knowledge of the pretrained language model. Then, we instruct-tune an open-source language model, called LLaMA, using this evidence, enabling it to predict the veracity of the input claim more accurately. To evaluate our method, we conducted experiments on two widely used fact-checking datasets: RAWFC and LIAR. The results demonstrate that our approach achieves state-of-the-art performance in fact-checking tasks. By integrating external evidence, we bridge the gap between the model’s knowledge and the most up-to-date information available, leading to improved fact-checking outcomes. Our findings have implications for combating misinformation and promoting the dissemination of accurate information in online platforms.

## Datasets

The raw datasets can be downloaded at [CofCED](https://github.com/Nicozwy/CofCED).
