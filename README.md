# restaurant-search

This script loads and preprocesses a dataset for named entity recognition (NER) tasks using pandas and the Hugging Face Transformers library. It tokenizes the input text, aligns the labels with the tokens, and creates a dataset dictionary containing the train, test, and validation datasets. The script then uses the Trainer class to fine-tune a pre-trained model on the training data, saving the trained model and using it to create a pipeline for NER tasks.
