# Synthetic Dataset Generation
With [YourBench](https://github.com/huggingface/yourbench) framework from HuggingFace, generated two synthetic evaluation datasets consisting of questions-answer pairs:

* [nor_agriculture_bench](https://huggingface.co/datasets/norjordAI/nor_agriculture_bench) - single hop open ended questions, oriented to a farmer, specific to one topic
* [nor_agriculture_multi_hop_questions_bench](https://huggingface.co/datasets/norjordAI/nor_agriculture_multi_hop_questions_bench) - multi hop open ended questions, covering multiple topics with focus on a specialist in agriculture

## Input data

As input, I used text data [About Norwegian Agriculture](https://www.kaggle.com/datasets/bugaiovaolena/about-agriculture-in-norwegian-language) from Kaggle collected earlier and then preprocessed with the notebook [Organising text for yourbench](https://www.kaggle.com/code/bugaiovaolena/organising-text-for-yourbench)
