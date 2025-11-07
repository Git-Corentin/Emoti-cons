# 
Authors : 

## Abstarct

This work explores how textual and embedding-based representations capture the emotional semantics of emojis. 
The main goal here is to assess the coherence between human-annotated emotion scores and computational emotion representations that are derived from emoji textual definitions and social media usage data.

We reach this aim by utilizing several different natural language processing techniques. 
First, more traditional word embedding models-Word2Vec, GloVe, and FastText-compute the vectors of emotion similarity, which are then compared with the human annotations of the EmoTag1200 dataset using Pearson correlation. 
Next, we apply contextual and lexical embeddings to large-scale tweet datasets for modeling semantic distances among emojis, represented with t-SNE. 
Further, topic modeling approaches like LDA and BERTopic map emoji-related tweet corpora into emotion spaces, thus facilitating data-driven emotion alignment. 
We also test the DeepMoji model on emoji prediction from text and carry out antonymy-based lexical analysis regarding semantic opposition between emojis.

Results indicate that subword and transformer-based embeddings excel at modeling the nuances of affect compared to classical models. 
Among these, FastText and DistilBERT show the best alignment with human emotion labels. 
BERTopic results in a higher coherence measure of topics than LDA, on average with a cosine similarity of approximately 0.73, while DeepMoji performs well in the top-5 prediction accuracy for unambiguously emotional emojis, reaching 0.71. 
Antonymy analysis shows weak lexical opposition, pointing out limitations with regard to using symbolic methods to model the emotion of multimodal communication.

In all, this work demonstrates the value of contextual embeddings and transformer-based topic modeling toward the emotion-aware analysis of text and emoji. 
It contributes to the field of affective computing, and by extension, sentiment analysis, integrating the linguistic and visual modalities to provide insights for more emotionally intelligent natural language processing systems.

## The code

There are 3 ipynb 
- Emoticons1-3.ipynb focuses on Word2Vec embedding compared with human annotations
- Emoticons4-6.ipynb focuses on defining distances between two emojis
- Emoticons7-9.ipynb focuses on topic modelling, emoji prediction and antonymy analisis
