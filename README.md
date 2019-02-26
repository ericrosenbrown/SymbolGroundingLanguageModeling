# SymbolGroundingLanguageModeling

TODO:
- Play with GPT-2, find 2 classes from imagenet that we can get a nice w to put into GPT-2 to get probabilities over class labels
- Get a random image-captioning architecture from online to convert images to probability distriubtion over our vocabulary (In Progress.... going to use the architecture from Show Attend and Tell. adding functionality to tune)
- take image captioning model, take GPT-Z, take w, and do KL divergence between two models conditioned on w.
    - beam search to sample both of these models
