# Project4_NYT

For this project there are 7 documents: My initial proposal, my powerpoint presentation, my summary of the work I've done,
and 4 jupyter notebooks of code.  The first three are fairly self-explanatory, but I'll give brief summaries of what each
notebook is about.\

The first notebook (00) is simply importing my data and creating the appropriate columns that I'll be using later on.\
The second notebook (01) is creating my classification/prediction algorithm.  In this I have my start to finish NLP pipeline:
I tokenize/preprocess the words, use CountVec to vectorize the inputs, use LSA to reduce the dimensionality, and then feed
these vectors into different classification algorithms.  I also graph my models to determine which is the best to use.\
The third notebook (02) is where I demonstrate why I chose to use 10 vectors from LSA.
The fourth notebook (03) is my unsupervised topic modeling, where I look at what topics were common in high-comment and 
low-comment articles.  I also demonstrate using the same technique with TFIDF.\
The final notebook (04) is scrap - it's models that I tried working with and ended up discarding, but thought the code might
be useful.
