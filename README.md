# Adversarial-Prompt-Engineering-for-Large-Language-Models-LLM-Jailbreaking

ECE-GY 9163 Machine Learning for Cyber-security || Project || Fall 2024 <br />
New York University (NYU) Tandon School of Engineering <br /> <br />

## Abstract
This project explores the application of KOV Monte Carlo Tree Search (MCTS) in adversarial prompt crafting for GPT-3.5 Turbo. By leveraging insights from prior research and implementing three experimental tasks: baseline evaluation, hyperparameter tuning, and surrogate model & hyperparameter optimization. Our study identifies configurations that enhance the success of adversarial bypass attempts. Our approach demonstrates an improvement over baseline models, emphasizing the importance of heuristic-driven methods for jailbreaking advanced language models.
<br />

## Note
Please go through the [documents]() folder for more info (like report, readme & requirements files)!
<br />

## Conclusion
In this work, the KOV Monte Carlo Tree Search (MCTS) algorithm was used for the adversarial prompt engineering approach for GPT-3.5 Turbo. Through the systematic examination of baseline settings, hyperparameters, and surrogate model improvements, the study identified important findings in improving the adversarial impact of prompts. The baseline results showed that GPT-3.5 was robust against such attacks and proved that it is not easy to bypass the safety measures of GPT-3.
<br /> <br />
In Task 2, the hyperparameter tuning demonstrated that the combination of topk and n_tokens was critical for the creation of adversarial prompts. However, more extended suffixes and higher diversity were beneficial; however, the coherence was sometimes sacrificed. In Task 3, where GPT-2 XL was used as the surrogate model, the importance of architecture specialization for adversarial performance was highlighted. However, GPT-2 XL outperformed Vicuna-7B even though it has a smaller size, and it obtained 474.32% of the improvement over the baseline with the best configurations. 
<br /> <br />
The results reveal the promise of heuristic-driven approaches such as KOV-MCTS to identify weaknesses in sophisticated language models as well as the costs of efficiency in terms of adversarial effectiveness. This work offers strong groundwork for further research on adversarial actions in use of large language models and protects the fields of AI ethics and cybersecurity.
<br /> <br />

## References
Mentioned in the report available in [documents]() folder.

## Team Members
1. Durga Avinash Kodavalla | dk4852 <br />
2. Ark Pandey | ap8652 <br />
3. Giorgi Merabishvili | gm3386 <br />
