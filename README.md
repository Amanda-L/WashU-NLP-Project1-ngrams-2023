# WashU NLP Project 1: ngrams 
This project addresses two distinct problems. Firstly, the implementation involves computing unsmoothed N-grams by preprocessing text through the removal of punctuation, extra white spaces, and <unk> tokens. The n_gram function is then applied to calculate and update the occurrence counts of unigrams, bigrams, and trigrams in the given context. Additionally, the model is trained on the wikitext-2-v1 corpus, and the top 10 most frequent unigrams, bigrams, and trigrams are printed. Moving on to Problem 2, which centers on Word Embeddings, the project involves implementing functions like cosine_similarity to calculate similarity between vectors and most_similar to find words similar to specified inputs. The second part of Problem 2 requires using word embeddings to solve analogies, demonstrating the ability to handle multiple positive and negative words for analogy-solving through the implementation of the most_similar_robust function.

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
- Solve analogies (e.g., dog:puppy :: cat:?, man:king :: woman:?, france:wine :: england:?).
- Implement `most_similar_robust` to handle multiple positive and negative words for solving analogies.

## Discussion
### Provide explanations for the differences between the most common unigrams, bigrams, and trigrams based on the obtained results.
Unigrams capture more articles, conjunctions, prepositions, and adverbs.

Bigrams are pairs of adjacent words that frequently occur together. They represent two-word combinations, or "collocations".

Trigrams are sequences of three words that occur together frequently. Some of them seem to represent specific phrases. (e.g., one of the, the united states, and as well as.)



