# cmpe258-team-project
# Contradictory, My Dear Watson

This project is based on active Kaggle competition named as “Contradictory-My Dear Watson”.

In this project, we’re classifying pairs of sentences (consisting of a premise and a hypothesis) into three categories - entailment, neutral and contradiction.
(0 for entailment, 1 for neutral, 2 for contradiction)

# Dataset
Premise-hypothesis pairs in fifteen different languages, including: Arabic, Bulgarian, Chinese, German, Greek, English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, Urdu, and Vietnamese.

Training Samples: 12120, Testing Samples: 5195

Columns in Training Dataset:
![image](https://user-images.githubusercontent.com/36389195/144159973-8e83d644-3f47-4835-b616-b4d326140a08.png)


# Approaches used:
1. Traditional NLP (TF_IDF and Glove embeddings)
2. Laser-Embedding
3. Using Transformers (BERT and ROBERTa)
4. Using Simple Transformer Library  (XLMRoberta)

# Comparison of models:

![image](https://user-images.githubusercontent.com/36389195/144159114-cc2d2ab6-3dae-4148-b142-589cf734b9bf.png)

# Conclusion:
1. The predictions for different models were submitted on Kaggle leaderboard
2. The testing accuracy f 92.66% was achieved for XLMRoberta-large-xnli model with the Kaggle rank of 12.

![image](https://user-images.githubusercontent.com/36389195/144159573-617f85e9-1e8e-46c7-97b0-e4f32001ae67.png)

# Citations:
1. https://www.kaggle.com/c/contradictory-my-dear-watson/data
2. https://simpletransformers.ai/docs/installation/
3. https://huggingface.co/models
4. https://engineering.fb.com/2019/01/22/ai-research/laser-multilingual-sentence-embeddings/ 
5. “Unsupervised Cross-lingual Representation Learning at Scale” at  arXiv:1911.02116
