# RESEARCH REPORT LINK 
https://docs.google.com/document/d/11OCTzzIjTH4CchZlIolv_u5UHDG1j1fFcCSI0NJhYeE/edit?usp=sharing

Please go through the report as it has my research in detail

## CUSTOM NER MODEL HAS BEEN HOSTED ON HUGGING FACES: 

https://huggingface.co/aryan10022001/en_predii_ner


## THE MODEL INFERENCE LINK

https://huggingface.co/spaces/aryan10022001/predii_ner

## llama model is stored here

https://huggingface.co/aryan10022001/llama-7b-train_quantized

# CUSTOM ENTITY RECOGNITION


In the automotive data analytics realm, extracting insights from vast data sets is crucial. With constant industry evolution driven by technology and consumer trends, precise data processing is essential. Custom entity recognition emerges as a key tool, enabling the identification and classification of specific entities within textual data.

This research project focuses on developing and evaluating a custom entity recognition model tailored for the automotive domain. Using advanced natural language processing techniques, the model aims to accurately identify vehicle models, features, components, and automotive terminology within textual data.

Accurate entity recognition is vital for downstream tasks like sentiment analysis, named entity recognition, and information extraction, providing deeper insights into consumer preferences, market trends, and product feedback.

By proficiently identifying and categorising automotive entities, this research aims to enable better data analysis, decision-making, and innovation within the automotive landscape.

# COMPARISON
SPACY model seems to be working much better and providing much better results because of the smaller size of spacy model,better BILOU tagging and Better encoding properties as it is based on BERT(BIDIRECTIONAL ENCODER REPRESENTATIONAL OF TRANSFORMERS)
While llama-7B is very much capable of doing ner ,but since i have the constraints of GPU and and thus token size is very small for inference and hence the results are not that good
Another Reason is that Due to constraints of GPU, i had to use quantization which may have affected the performance
While the spacy model is very high in performance , it has one limitation of smaller context .

# RESULTS:
In my opinion the spacy model have worked very good in determining the custom entities of the dataset than llama-7b.
Llama-7b  would have provided better results given that if I had the enough resources.



