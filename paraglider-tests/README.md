
# LLM powered queries on glider certification documents

## Document sources

* [Air Tourquoise](https://para-test.com)
* (todo) DHV

Use [notebook](./glider_classification_source.ipynb)

Files are downloaded to `data/pdf`, which folder should exist.


## Query chain

Mostly using the [langchain](https://python.langchain.com/) library

### Embeddings

Open AI with `text-embedding-ada-002` should work well

### Vector store & retriever

Both Chrome / FAISS seem to work.

### LLM

Open AI gpt 3

### Queries

Some questions work better than others.

![looks ok](example.PNG)
![not so good](not_so_good_example.PNG)









