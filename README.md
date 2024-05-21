# Movie review Analyzer
Analyses movie reviews &amp; predicts a probability of how good (close to 1) or how bad (close to 0) a movie review is. 


We train a sentiment analysis model using the BERT (Bidirectional Encoder Representations from Transformers) model, introduced [here](https://arxiv.org/abs/1810.04805). Specifically, we will parse movie reviews and classify their sentiment (according to whether they are positive or negative.)

Used[link text](https://) [Huggingface transformers library](https://github.com/huggingface/transformers) to load a pre-trained BERT model to compute text embeddings, and append this with an RNN model to perform sentiment classification.

Any questions: aashnakunk@gmail.com
