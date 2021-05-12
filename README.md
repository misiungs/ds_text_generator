# Natural language processing: text generation
NLP project about text generation

<img src="https://github.com/misiungs/readme_images/blob/master/books.jpg?raw=true" alt="drawing" width="500"/>

# Problem
The project goal is to create a language model that will be able to write in a style of a specific author.
Here we will try to mimick a style of Agata Christie based on some of her books.

# Approach
Six Agata Christie's books has been gathered from Gutenberg's project website.
Three different language model are considered: a simple n-gram model, recurrent neural networks with LSTM cells and a fine-tuned GPT-2 transformer.
For each of the models a dataset has been preprocessed and the models has been built.
Based on a few starting words examplary texts have been generated and analysed.
Infulence of hyperparameters such as temperature or top-k sampling has been also investigated.

# Conclusions
With the increase of the models sophistication the results become more coherent and similarrity to the author's style increases.
The GPT-2 yields results that could easily be mistaken with the true book fragments.

