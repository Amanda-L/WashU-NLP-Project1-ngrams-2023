# WashU-NLP-Project1-ngrams2023

Summary of the assignment:

### Problem 1: N-grams

#### 1.1 Compute Unsmoothed N-grams
- Implement `remove_punctuation` to preprocess text by removing punctuation, extra white spaces, and `<unk>` tokens.
- Implement `n_gram` to calculate n-grams (unigrams, bigrams, trigrams) and update their occurrence counts in the context.

#### 1.2 Train the Model on the wikitext-2-v1 Corpus
- Use the implemented `n_gram` function to calculate unigrams, bigrams, and trigrams.
- Print out the top 10 most frequent unigrams, bigrams, and trigrams.

### Problem 2: Word Embeddings

#### 2.1 Finding Similar Words
- Implement `cosine_similarity` to calculate the cosine similarity between two vectors.
- Implement `most_similar` to find the most similar words to specified input words.

#### 2.2 Using Word Embeddings to Solve Analogies
- Implement `most_similar_robust` to handle multiple positive and negative words for solving analogies.
- Solve analogies (e.g., dog:puppy :: cat:?, man:king :: woman:?, france:wine :: england:?).

# Discussion
## Provide explanations for the differences between the most common unigrams, bigrams, and trigrams based on the obtained results.
Unigrams capture more articles, conjunctions, prepositions, and adverbs.

Bigrams are pairs of adjacent words that frequently occur together. They represent two-word combinations, or "collocations".

Trigrams are sequences of three words that occur together frequently. Some of them seem to represent specific phrases. (e.g., one of the, the united states, and as well as.)



