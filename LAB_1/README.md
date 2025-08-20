# Assignment 1: Hindi Language Tokenization  

## 📌 Overview  
This assignment focuses on building a tokenizer for the **Hindi language** that can handle sentences, words, and special cases such as punctuation, numbers, URLs, email IDs, and dates. The processed tokens are then used to compute corpus-level statistics.  

## ✨ Features Implemented  
- **Sentence Tokenizer**: Splits text into sentences.  
- **Word Tokenizer**: Splits each sentence into individual words.  
- **Special Handling**:  
  - Punctuation  
  - URLs  
  - Numbers (including decimals)  
  - Email IDs  
  - Dates  
- **Corpus Statistics Computed**:  
  1. Total number of sentences  
  2. Total number of words  
  3. Total number of characters  
  4. Average sentence length (words per sentence)  
  5. Average word length (characters per word)  
  6. Type/Token Ratio (TTR) (unique tokens / total tokens)  

## 📂 Dataset  
- Dataset Source: [IndicCorpV2 - Hindi](https://huggingface.co/datasets/ai4bharat/IndicCorpV2)  
- Data was downloaded and extracted locally.  
- The tokenizer was applied to this dataset to perform tokenization and statistics computation.  