# Language Models for Ontology Prediction

This repository includes early work on ontology validation using distil-GPT2 in the Huggingface Transgformer package with PyTorch. The interactive notebook defines a measure for annotation validity which is expressed as a posterior probability ratio (with positive being more likely). The measure can be determined with or without a domain-specific context which will bias the model toward a specific area of the annotation space.

As part of the calculation, the model takes ontology terms and converts the relations between them into plain text which can be interpreted by the LLM as a more or less probable extension of the context.

The next version will look at the probability of one ontology term being a natural extension of another or a set of other terms. In this way ontological terms can be validated within their own context.
