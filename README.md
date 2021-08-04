# Game of Thrones NLP Analysis

In this notebook I will try to analyze the scripts of one of the most popular and controversial TV shows of all time: **Game of Thrones**. The dataset used was taken from [Kaggle](https://www.kaggle.com/albenft/game-of-thrones-script-all-seasons) and contains each script line of the series, with corresponding speaker's name, episode and season. 

The reason I chose this dataset is that, besides being a fan myself, the show went from being a massive and very praised pop culture phenomenon, to being absolutely hated by most of its fanbase, who critisized its finale (season 8 and, to some extent, season 7). If fans critisize the plot and the plot is contained in the scripts, we may be able to observe a difference in semantics between the first and last seasons.

The notebook is organized as follows. Firstly, the data is preprocessed. Secondly, a number of NLP techniques are used to analyze the script of the series. In particular, we check for semantic differences between characters and between different seasons. Then, a simple language model is used to try and generate a new script of the show. Finally, various dimensionality reduction and visualization techniques are used to make sense of the results.

The NLP techniques and algorithms used in this notebook include:
- NLP preprocessing (stopwords, punctuation removal, lemmatization, etc.)
- Collocations
- Word and Document embeddings
- TF-IDF
- Language Models
- SVD
- Clustering
- t-SNE

Notice: this notebook was my midterm for a NLP class in my Data Science MSc. 
