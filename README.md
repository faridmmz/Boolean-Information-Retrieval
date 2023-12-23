# Boolean Information Retrieval
<<<<<<< HEAD

This project was truly interesting to us as it helped us learn the interesting world of text processing and how it comes to aid the information retrieval field. 

This python Notebook covers various text processing tasks for both English and Farsi language datasets. The tasks include tokenization, normalization, stemming, and stop-word removal. Additionally, it implements a Boolean Information Retrieval (IR) model using inverted indexing and term occurrence matrices.

## Libraries Used 
 
- `hazm` : A Python library for working with the Persian language.
- `nltk` : Natural Language Toolkit for English language processing.
- `pandas` : Data manipulation and analysis library.
- `re` : Regular expression operations.
- `pickle` : Serialization and deserialization of Python objects.

## Data Sources
### English Dataset
- [Movie Summaries](http://www.cs.cmu.edu/~ark/personas/data/MovieSummaries.tar.gz) : Dataset containing movie summaries.

### Farsi Dataset
- [Persian PDF Books Dataset](https://github.com/mohamad-dehghani/persian-pdf-books-dataset/raw/master/final_books.xlsx) : Collection of Farsi books information. 

## Functions Implemented
1. **Inverted Index: `build_inverted_index`**
   - Creates an inverted index for a given DataFrame and column.

2. **Save Inverted Index to File `save_invertedindex_to_file`:**
   - Saves the inverted index to a pickle file.

3. **Term Occurrences: `build_term_occurences`:**
   - Builds a term occurrence matrix.

4. **Process English Term: `process_english_term`:**
   - Normalizes and stems English terms.

5. **Process Farsi Term: `process_farsi_term`:**
   - Normalizes and stems Farsi terms.

6. **Process Query: `process_query`:**
   - Processes user queries based on language.

7. **Search Documents: `search_documents`:**
   - Implements Boolean Information Retrieval.

8. **Count Tokens and Documents: `count_tokens_and_documents`:**
   - Calculates the total tokens and documents in a DataFrame.

## Dataset Preprocessing

- Download and extract the Movie Summaries and Persian PDF Books dataset.
    
- Tokenize, normalize, stem, and remove stopwords from the dataset.
    
- Build the inverted index and term occurrence matrix.


## Boolean Information Retrieval

- Implemented Boolean Information Retrieval using the created matrices.
    
- Used Boolean operators (AND, OR, NOT) for document retrieval.
## How to Use
1. Install the required libraries using the provided pip command.
2. Run the notebook cells sequentially for each language section (English and Farsi).
3. Follow the steps for tokenization, normalization, stemming, and stop-word removal for each language.

For any inquiries or further information don't hesitate to contact us!


=======
This repository contains our team assignments and projects from the Intro to Information Retrieval Course.
>>>>>>> 500ef81528ce471225686260e7ed1e888dfd1eae
