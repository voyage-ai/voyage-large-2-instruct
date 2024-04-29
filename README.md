# voyage-large-2-instruct
`voyage-large-2-instruct` is an instruction-tuned general-purpose embedding model optimized for clustering, classification, and retrieval. For general retrieval tasks, please use [`input_type`](https://docs.voyageai.com/docs/embeddings#python-api) argument, which adds instructions on the backend. 

For classification (or clustering) tasks, please set `input_type` to `None` and prepend "Classify the text: " (or "Cluster the text: ") to your texts. 

For [MTEB](https://huggingface.co/spaces/mteb/leaderboard) subtasks, please refer to `instruct.json` for the instruction. Similar to classification and clustering use cases, please set `input_type` to `None` and prepend the instruction to your texts.