In this folder we present two different ways to apply a data augmentation. The objective is to create from a sentences a new one with different words but with the same meaning. 

One option is to use random synonym replacement.Here we show a notebook using the `most_similar` genism library method that allows connecting words with similar meanings, 
based on the similarity of the contexts in which they are used. The limits using this type of DA are: 
  * You can't create new information to feed a neural network because the text is not different at all. 
  * Synonym replacement can't achieve the propoused goal because it's not really clear that some synonym has the same meaning although it's used in the similar context. 

The other manner is to use the GPT-2 algorithm, developed by Open-AI, that allows to create totally new lines of text, because the vectors are trained with huge amounts of data
located in internet. GPT-2 allow us to reach 0.80845 points in the Kaggle competition score. 
