# Naive_Bayes_for_Word_Sense_Disambiguation_NLP

I built a Naive Bayes model on classification (of senses for ambiguous words). I have selected a number of contexts which share the same words the algorithm has been tested on ("line"/"interest"/"hard"/"serve"), and selected the most common words for each context.
The most common words and the words around the target word in the context (not fartger than a fixed windows size) are treated as features, except stop words.
Next, I calculated the probabilities for each sense for each target word using the formulas:

![image](/images/formula1.jpg)
![image](/images/formula2.jpg)
![image](/images/formula3.jpg)

###After experimenting with the window size and the number of most common words from each context, the accuracy results are:

"Line": 96.78%

"Hard": 99.84%

"Serve": 99.23%

"Interest": 98.59%
