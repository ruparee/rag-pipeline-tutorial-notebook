https://ollama.com/library/all-minilm:l6-v2/blobs/797b70c4edf8
ollama pull all-minilm:l6-v2

general.name - all-MiniLM-L6-v2

l6-v2
10 Tags
ollama pull all-minilm:l6-v2

all-minilm:l6-v2
/
model
797b70c4edf8 · 46MB
Metadata
bert.attention.causal
false
bert.attention.head_count
12
bert.attention.layer_norm_epsilon
1e-12
bert.block_count
6
bert.context_length
512
bert.embedding_length
384
bert.feed_forward_length
1536
bert.pooling_type
1
general.architecture
bert
general.file_type
1
general.name
all-MiniLM-L6-v2
tokenizer.ggml.bos_token_id
101
tokenizer.ggml.cls_token_id
101
tokenizer.ggml.eos_token_id
102
tokenizer.ggml.mask_token_id
103
tokenizer.ggml.model
bert
tokenizer.ggml.padding_token_id
0
tokenizer.ggml.scores
[-1000, -1000, -1000, -1000, -1000, ...]
tokenizer.ggml.seperator_token_id
102
tokenizer.ggml.token_type
[3, 1, 1, 1, 1, ...]
tokenizer.ggml.token_type_count
2
tokenizer.ggml.tokens
[[PAD], [unused0], [unused1], [unused2], [unused3], ...]
tokenizer.ggml.unknown_token_id
100
Tensor












https://ollama.com/library/all-minilm:22m
The project aims to train sentence embedding models on very large sentence level datasets using a self-supervised contrastive learning objective.

# Usage

## REST API
```bash
curl http://localhost:11434/api/embeddings -d '{
  "model": "all-minilm",
  "prompt": "The sky is blue because of Rayleigh scattering"
}'

```
##  Python library

```groovy
ollama.embeddings(model='all-minilm', prompt='The sky is blue because of Rayleigh scattering')
```

##   Javascript library
```js
ollama.embeddings({ model: 'all-minilm', prompt: 'The sky is blue because of Rayleigh scattering' })
```
References
HuggingFace

Website

