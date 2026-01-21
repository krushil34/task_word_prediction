# lstm word prediction using Shakespeare Dataset

This project implements a **word-level text generation model using LSTM (Long Short-Term Memory)** networks.  
The model is trained on **Shakespeare’s complete works** and generates coherent text given a seed sequence.

---

##  Project Overview

- **Task**: Train an LSTM model to generate text
- **Approach**: Next-word prediction using a sliding window
- **Model Type**: Word-level LSTM
- **Framework**: TensorFlow / Keras
- **Dataset**: Shakespeare (Project Gutenberg)

---

##  Dataset

**Source**: Project Gutenberg  
 https://www.gutenberg.org/ebooks/100

The dataset is scraped directly from the Gutenberg website and contains a large body of public-domain literary text.

---

##  Preprocessing Steps

1. Download and extract text using `requests` and `BeautifulSoup`
2. Convert text to lowercase
3. Remove punctuation and special characters
4. Tokenize text into word indices
5. Create fixed-length input sequences using a sliding window
6. Predict the **next word** as the target



