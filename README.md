# Leveraging BERT for Natural Language Understanding of Domain-Specific Knowledge
 We experiment with fine-tuning BERT to jointly detect the user’s intent and the related slots, using a custom-generated dataset built around a organization specific
knowledge base. Our results show that well-constructed datasets lead to high detection performances and the resulting model has the potential to enhance a future task-oriented dialogue system.

The model is part of a wider project, as it is trained using datasets generated with our Dialogue Simulator (https://github.com/IonutIga/Dialogue-Simulator/). It is intended to be incorporated as its NLU module, replacing the rule-based approach currently available in the system. More details available in the attached paper.

V1.1 version of the notebook has added functionality for converting text formatted data (ATIS, SNIPS) into JSON format, while keeping all original labelings. 
