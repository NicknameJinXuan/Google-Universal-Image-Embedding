# Google-Universal-Image-Embedding

# Description from Kaggle
https://www.kaggle.com/competitions/google-universal-image-embedding

Welcome to the Universal Image Embedding competition! After hosting challenges in the domain of landmarks for the past four years, this year we introduce the first competition in image representations that should work across many object types.

Image representations are a critical building block of computer vision applications. Traditionally, research on image embedding learning has been conducted with a focus on per-domain models. Generally, papers propose generic embedding learning techniques which are applied to different domains separately, rather than developing generic embedding models which could be applied to all domains combined.

In this competition, the developed models are expected to retrieve relevant database images to a given query image (ie, the model should retrieve database images containing the same object as the query). The images in our dataset comprise a variety of object types, such as apparel, artwork, landmarks, furniture, packaged goods, among others.

This year's competition is structured in a representation learning format: you will create a model that extracts a feature embedding for the images and submit the model via Kaggle Notebooks. Kaggle will run your model on a held-out test set, perform a k-nearest-neighbors lookup, and score the resulting embedding quality. Both Tensorflow and PyTorch models are supported.
