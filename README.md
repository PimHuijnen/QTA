# QTA2023

This is the repository for the 2023/24 quantitative text analysis module of the Methods course in the research master program History at Utrecht University (see: https://www.uu.nl/en/masters/history). See the course manual in the folder with the same name.

The _notebook_ folder contains a series of Jupyter Notebooks. The _Sample data_ folder contains some example text files (see below). The aim of the notebooks is to provide an introduction to quantitative text analysis (text mining). The notebooks are structured as listed below. Most notebooks take .txt files as input, but can be tweaked very easily to import .csv files. Text files are ideally chronological and named for the year they represent (for example '1981.txt', '1982.txt', etc.).

## Notebooks

**Doing things with text 1** - Preprocessing of a single text file (.txt): 
<ul>
  <li>remove html, punctuation, numbers, short words, stopwords; lowercase</li>
  <li>save cleaned text to file</li>
  <li>basic statistics of text</li>
</ul>

**Doing things with text 2** - word counts on a single, preprocessed text file (.txt):
<ul>
  <li>most common words as bar chart</li>
  <li>most common words as word cloud</li>
  <li>most common words by word length</li>
</ul>

**Doing things with text 3a** - Preprocessing and word counts on multiple text files (.txt, raw or preprocessed):
<ul>
  <li>same as Doing things with text 1 and 2 but for multiple text files</li>
</ul>

**Doing things with text 3b** - Preprocessing and word counts on multiple .csv files (raw text):
<ul>
  <li>same as Doing things with text 1 and 2 but for one or more csv files</li>
</ul>

**Doing things with text 4** - Text analysis (for multiple .txt files, preprocessed):
<ul>
  <li>plot word / n-gram frequency per file in a scatter plot</li>
  <li>print collocations (log likelihood, pmi, raw frequency) of one or more keywords per file</li>
  <li>print top n-grams per file</li>
</ul>

**Doing things with text 5** - tf-idf with gensim (for multiple .txt files, preprocessed):
<ul>
  <li>plot top distinct words (tf-idf) per file in a bar chart</li>
  <li>create heatmap for cosine similarity</li>
</ul>

**Doing things with text 6** - part-of-speech with spacy (for multiple .txt files, preprocessed):
<ul>
  <li>print most common words of a particular type (adjective, verb, (proper) noun) per file</li>
  <li>print most common named entities per file</li>
</ul>

**Doing things with text 7** - word embeddings with gensim's word2vec (for multiple .txt files, raw or preprocessed):
<ul>
  <li>train word2vec model on dataset</li>
  <li>search most similar terms for one or more keywords</li>
  <li>plot most similar terms as clusters in a t-sne plot</li>
</ul>

## Sample data
<ul>
  <li>screenplays for Star Wars I - VII as .txt</li>
  <li>screenplays for a series of movies about science/scientists as .csv</li>
</ul>
