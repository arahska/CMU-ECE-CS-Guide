Paper : QA-GNN: Reasoning with Language Models and Knowledge 

Graphs for Question Answering 

Citation: 

Michihiro Yasunaga, Hongyu Ren, Antoine Bosselut, Percy Liang, and Jure Leskovec. 2021. QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering. In *Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies*, pages 535– 546, Online. Association for Computational Linguistics. 

The authors aim to give answers to natural language questions using both pre-trained language models (LM) and knowledge graphs (KG) to perform legible and well-structured reasoning like handling negation in questions for multiple choice QA tasks. They propose the QA-GNN model that combines broad coverage in LM to extract QA context and structured reasoning in KG to derive a subgraph, giving way to a joint graph with an additional QA context node. 

Using LM to build a relevance score between the QA context node and every other node, the attention-based GNN module helps in making a final prediction to provide semantic relevance to the extracted KG subgraph for answering tasks. The authors achieved +5.7% improvement over fine- tuned LMs and +3.7% over existing LM+KG models on OpenBookQA dataset using RoBERTa-large LM and ConceptNet KG . This paper can be helpful in deriving insights on how to approach our answering task from a LM+KG perspective to achieve structured reasoning in answers. 
