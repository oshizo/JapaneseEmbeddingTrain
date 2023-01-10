# JapaneseEmbeddingTrain

Jupyter notebook for training sentence-transformers models with JSNLI.
The training script is a slightly modified version of the [NLI example Sentence-transformers repository](https://github.com/UKPLab/sentence-transformers/blob/master/examples/training/nli/training_nli_v2.py).

## Trained Models

* [oshizo/sbert-jsnli-luke-japanese-base-lite](https://huggingface.co/oshizo/sbert-jsnli-luke-japanese-base-lite/)
  * This model was trained 1 epoch on Google Colab Pro A100 and took approximately 40 minutes.

## Evaluation

* https://github.com/oshizo/JapaneseEmbeddingEval
