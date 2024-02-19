In the summary.ipynb notebook, prompt engineering (zero shot, one shot, and few shot inferences) is explored to check the effect of the input text. 

In the fine-tuning.ipynb notebook, Parameter Efficient Fine-Tuning (PEFT) is used to fine-tune FLAN-T5 LLM on summarization task. 
For evaluatation, I use the ROUGE metrics. 

In the finetuning_rl.ipynb, I fine-tuned a FLAN-T5 model to generate less toxic content with Meta AI's hate speech reward model. The reward model is a binary classifier that predicts either "not hate" or "hate" for the given text. I used Proximal Policy Optimization (PPO) to fine-tune and reduce the model's toxicity.
