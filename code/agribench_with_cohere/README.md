# Synthetic Dataset Generation
With [YourBench](https://github.com/huggingface/yourbench) framework from HuggingFace and Cohere [Commad A](https://docs.cohere.com/docs/command-a) model, generated a synthetic evaluation dataset [Norwegian Agriculture Bench with Cohere model](https://huggingface.co/datasets/norjordAI/nor_agriculture_bench_with_cohere_model) consisting of questions-answer pairs:
* single-hop open ended questions, specific to one topic, with focus on farmers
* multi-hop open ended questions, covering multiple topics with focus on a specialist in agriculture

## Input data

As input, I used text data [About Norwegian Agriculture](https://www.kaggle.com/datasets/bugaiovaolena/about-agriculture-in-norwegian-language) from Kaggle collected earlier and then preprocessed with the notebook [Organising text for yourbench](https://www.kaggle.com/code/bugaiovaolena/organising-text-for-yourbench)
