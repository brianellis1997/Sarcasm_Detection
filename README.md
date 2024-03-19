# Sarcasm_Detection
Utilizing NLP techniques to build traditional and deep machine learning models to detect the presence of sarcasm.

# HuggingFace Model
Here you can directly impute your text to receive classifcation from our model: https://huggingface.co/brianellis1997/distilbert-sarcascm-classifier
<br>To maximize the classifcation confidence, suggested format is 'parent_comment: {your text} child_comment {your text}". This is because the model was trained on Reddit data including a parent comment and child comment and was given those prompts during training.
