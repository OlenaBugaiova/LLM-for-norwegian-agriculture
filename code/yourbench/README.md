# Synthetic Dataset Generation
With [YourBench](https://github.com/huggingface/yourbench) framework from HuggingFace, [Normistral](https://huggingface.co/norallm/normistral-11b-thinking) and  [Cohere](https://huggingface.co/norallm/normistral-11b-thinking) models, generated two synthetic evaluation datasets of questions-answer pairs:

Single hop open-ended questions, specific to one topic, focused on a farmer:
* [nor_agriculture_bench](https://huggingface.co/datasets/norjordAI/nor_agriculture_bench)
* [nor_agriculture_bench_with_cohere_model](https://huggingface.co/datasets/norjordAI/nor_agriculture_bench_with_cohere_model)

Additionally, generated a multi hop open-ended questions, covering multiple topics with focus on a specialist in agriculture [nor_agriculture_multi_hop_questions_bench](https://huggingface.co/datasets/norjordAI/nor_agriculture_multi_hop_questions_bench)

## Input data

As input, I used text data [About Norwegian Agriculture](https://www.kaggle.com/datasets/bugaiovaolena/about-agriculture-in-norwegian-language) from Kaggle collected earlier and then preprocessed with the notebook [Organising text for yourbench](https://www.kaggle.com/code/bugaiovaolena/organising-text-for-yourbench)
