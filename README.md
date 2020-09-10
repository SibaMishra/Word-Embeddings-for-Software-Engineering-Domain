# Word-Embeddings-for-Software-Engineering-Domain

In this repository, we are making our pre-trained word embeddings based word2vec model (in .bin) freely available for reuse. The model have been trained by crawling and extracting the Wikipedia pages for the "software engineering" category with a depth of 4. We have trained the model using HP Z4 G4 workstation with Intel(R) Core(TM) i9-7900X CPU, 32GB RAM, 3.30GHz clock, 10 cores and 20 logical processors. The model parameters are finalized after performing several round of experiments.


# For running the model, use the below-mentioned source

 import gensim
  
 model = gensim.models.KeyedVectors.load_word2vec_format('path', binary = True)


In case of any difficulty, you can contact us.
