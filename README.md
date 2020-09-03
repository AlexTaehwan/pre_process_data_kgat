# Usage
Pre-process the three data sets (amazon-book, last-fm, and yelp2018) from kgat paper

## Data type
```bash
rel2id.txt : relation to id dictionary (format : {"relationship" : id})
vocab_id_dict.txt : entity + user to id dictionary (format : {entity or user : id})
normalized_kb_final.txt : knowledge graph from entity (format : source_id, relation, vocab_id)
test.txt : test data (format : user_id, user_interaction_id (from rel2id.txt), item_id)
train.txt : train data (format : user_id, user_interaction_id (from rel2id.txt), item_id)
``` 