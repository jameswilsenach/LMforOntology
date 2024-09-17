# Language Models for Ontology Prediction

This repository includes early work on ontology validation using distil-GPT2 in the Huggingface Transgformer package with PyTorch. The interactive notebook defines a measure for annotation validity which is expressed as a posterior probability ratio (with positive being more likely). The measure can be determined with or without a domain-specific context which will bias the model toward a specific area of the annotation space.

The current version takes only ontology terms and converts the relations between them into plain text which can be interpreted by the LLM as more or less probable.
