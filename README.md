Visualizing Embeddings
---

This repository houses the code and data for visualizing various word embedding experiments using TensorBoard's projector.


### Visualizing Attention mechanism's "Learned Query Vector"

spaCy's text classifier uses an attention layer that **should** learn an optimal query vector for
selecting the most appropriate tokens given an input. This experiment tries to understand what the query 
vector learns by observing the change in its vector over time.

![alt text](https://github.com/justindujardin/projector/raw/ab50806029db3f7dea9d3064ce5ac7cb64fc7753/oss_data/spaCy_attn_learned_query_vector_preview.gif "Attention mechanism query vector learned over 200 training iterations")

[View interactive version](https://justindujardin.github.io/projector/)



### Credits

You can get a copy here: https://github.com/tensorflow/embedding-projector-standalone/


