# LLM-s
I am currently studying LLM's and I am building few projects
1. Translational model using the T5-flan model for translating sanskrit texts to english
2. Dataset used is - Itihaas (bilingual corpora for training the model)
The SANET model is currently at 0.52 (bleu score)
Bleu score is the evaluation metric used
Dataset used is Itihasa dataset.
Itihasa is a bilingual corpora of sanskrit sentences from epics of Mahabharat and Ramayan with their respective english translation.
Model used is Google -T5 small.
This model is finetuned on the itihasa dataset.

# RAGify
- an RAG based approach for automating the boring administrative and data entry tasks.
- I used basic documents (.pdf) from my college.
- used the Google t5 flan-large model to be the interactive chatbot model
- built a knowledge base to apply the RAG approach. The dataset used for the knowledge base is just some documents used for testing the ability of the LLM model
- aiming to reduce hallucination of the LLM.
  
# Creating a NLUI for my system using a transformer model
- I will be adding few features for my NLUI. There will be tasks that the NLUI would perform.
- These tasks are :
  1. Basic System Commands
  2. Recommend movies, restaurants etc.
  3. Suggesting games and activities to cure boredom
  4. Information retreival
  5. Weather and News
