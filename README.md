Multi-label Text Classification with BERT and PyTorch Lightning
TL;DR Learn how to prepare a dataset with toxic comments for multi-label text classification (tagging). We'll fine-tune BERT using PyTorch Lightning and evaluate the model.

Multi-label text classification (or tagging text) is one of the most common tasks you'll encounter when doing NLP. Modern Transformer-based models (like BERT) make use of pre-training on vast amounts of text data that makes fine-tuning faster, use fewer resources and more accurate on small(er) datasets.

In this tutorial, you'll learn how to:

Load, balance and split text data into sets
Tokenize text (with BERT tokenizer) and create PyTorch dataset
Fine-tune BERT model with PyTorch Lightning
Find out about warmup steps and use a learning rate scheduler
Use area under the ROC and binary cross-entropy to evaluate the model during training
How to make predictions using the fine-tuned BERT model
Evaluate the performance of the model for each class (possible comment tag)
