# Llama7Bing
This repository serves for the final project of Yale CPSC 477/577 Spring: A sarcastic language model learns from Chandler Bing

This project has two components: 

1. Supervised Fine Tuning (SFT) and Instruction Fine Tuning (IFT) of different SOTA LLMs on the sarcasm classification task of a public available dataset: https://github.com/EducationalTestingService/sarcasm/tree/master. 

2. Create a chatbot mimicing Chandler Bing's dialogue via direct policy optimization (DPO) using Friends' original script and hypothetically generated script by generative AI.

The following sections explain the function of each python coding file:

finetune_higgingface.ipynb: SFT of BERT and Llama2-7B model via huggingface.


gpt4_IFT.ipynb: IFT of gpt-3.5-turbo and gpt-4-turbo via openAI api.
