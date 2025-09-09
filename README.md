Exercice 1 : 

I constructed a pipeline for knowledge graph construction from raw text data. I performed the folowing taks : 

. Text Cleaning & Preprocessing: Clean and normalize the provided text dataset.
. Named Entity Recognition (NER): Train a CRF model to extract named entities from the cleaned
text, compare with spaCyʼs en_ner_conll03 pre-trained NER model.
. Relation Extraction (RE): Use spaCyʼs "en_core_web_sm" model to extract relations between the
identified entities.
. Knowledge Graph Building: Convert the extracted entities and relations into RDF triples and load
them into a graph database.
. Web Scrapping: Fetch and process web content from websites.
The tasks involves many NLP techniques that you haven't learnt so far, therefore, you are encouraged to
use Genarative AI tools (such as ChatGPT).

Exercice 2 :
In this part, I created and evaluated knowledge graph embeddings from my
constructed knowledge graph. I addressed the challenge of limited entity count through data
augmentation techniques.
